<!-- Reference-style links to make tables & lists more readable -->
[VCELiNK-Keystone]: <https://www.amazon.ca/stores/page/76F89957-8DA8-4230-91C8-5E17D49C24AA>
[PrimeCables-KeystoneAV]: <https://www.primecables.ca/c-1089-audio-video-keystone-jacks>
[InfiniteCables-SurfaceBox]: <https://www.infinitecables.com/collections/surface-boxes>

## Connectors

# Basic pin/socket jumper wiring:
<!----------------------------------------------------------------------------->
Adafruit starter kit: https://www.adafruit.com/category/306

Pre-crimped, ready to split:
- M/M: <https://www.adafruit.com/product/3142>
- F/F: <https://www.adafruit.com/product/3141>
- M/F: <https://www.adafruit.com/product/3633>
- Headers 1 row: [SMALL](https://www.adafruit.com/product/3145), [LARGE](https://www.adafruit.com/product/3146)
- Headers 2 rows: [SMALL](https://www.adafruit.com/product/3143), [LARGE](https://www.adafruit.com/product/3144)

# Advanced maker connectors:
<!----------------------------------------------------------------------------->
This section lists connectors popular with current maker boards, and their
application. More information can be found here:
- <https://learn.adafruit.com/introducing-adafruit-stemma-qt/stemma-qt-comparison>
- Good video show/tell (few types only): 🎞️<https://youtu.be/tBipTe69x-o?t=91>
- More reading: <https://www.tomshardware.com/features/stemma-vs-qwiic-vs-grove-connectors>

⚠️Warning
- Not all devices expect the same signal levels/power to be delivered on their
  connectors. Typical operating voltages in use at the time of writing are 5V
  and 3.3V. Please ensure proper level match/shifting is in order.
- Not all formats work together. Please refer to:<br>
  <https://learn.adafruit.com/introducing-adafruit-stemma-qt/stemma-qt-comparison#quick-comparison-3035247>

## JST-XH (2.5mm/0.1"/Medium)
> XH-Kit (Adafruit): <https://www.adafruit.com/product/4423>

- Breadboard/protoboard compatible pitch

## JST-PH (2mm/Small)
> PH-Kit (Adafruit): <https://www.adafruit.com/product/4422>

2-pin JST-PH (2mm):
- Some lithium-ion polymer ("Lipo") connectors (Adafruit: <https://www.adafruit.com/category/574>).
- Some battery holders (Adafruit: <https://www.adafruit.com/category/135>).
  <br>⚠️Warning: Do not connect batteries to products with Li-Ion/Poly charging ports!

3-pin JST-PH (2mm):
- [ADA/STEMMA (classic) device](https://www.adafruit.com/product/4336):
  Analog/Digital/PWM device (not I2C).
  <br>Don't think there are many.
- DFRobot/Gravity device (not I2C): [⚠️pin order does not line-up with other systems](https://learn.adafruit.com/introducing-adafruit-stemma-qt/dfrobot-gravity).

4-pin JST-PH (2mm):
- [ADA/STEMMA (classic) I2C](https://www.adafruit.com/product/3568)
- DFRobot/Gravity I2C: [⚠️pin order does not line-up with other systems](https://learn.adafruit.com/introducing-adafruit-stemma-qt/dfrobot-gravity).

## Grove (2mm/Small): Proprietary
Similar to JST-PH... but appear to be different.

4-pin Grove (2mm)
- [Grove I2C](https://www.adafruit.com/product/5244)
- [Grove dual-pin device](https://www.adafruit.com/product/5244)

## JST-SH (1mm/VERY Small)
3-pin JST-SH (1mm):
- [SWD ports (tiny)](https://www.adafruit.com/product/5765)

4-pin JST-SH (1mm):
- [ADA/STEMMA QT](https://www.adafruit.com/product/4399)
- [SparkFun/Qwiic](https://www.sparkfun.com/products/15081)

## Molex KK-254 (2.54mm/0.1"/Medium)
Larger (higher) than JST-XH.

## "Universal" Crimpers:
- Adafruit: <https://www.adafruit.com/category/622>

# D-subminiature (DB9/DB25/...)
<!----------------------------------------------------------------------------->
- Info: <https://en.wikipedia.org/wiki/D-subminiature>
- Large and bulky by today's standard.
- Form factor might be practical for many people.
- Used in alot of older equipment (typically [RS-232 communications](Communications.md#EIA_TIA_standards))
- DB9 breakout connector: <https://www.adafruit.com/product/3122>

# RJ-45 ("Ethernet")
<!----------------------------------------------------------------------------->
For all-around flexibility. [See section on Networking Connectors](ConnectorsNetworking.md).

Advantages:
- Cables are everywhere/easy to find.
- Larger size (easier to manipulate) - yet relatively compact.
- Comes in a bundle.
- Twisted into pairs to limit interference (assuming differential signalling).
- Cheap/easy to build.
- Keystone jacks are readily available \< [VCELiNK-Keystone] \>.
  <br>==> Can even use surface boxes as project boxes: \< [InfiniteCables-SurfaceBox] \>
  <br>==> And integrate with other Keystone connectors: \< [PrimeCables-KeystoneAV] \>

⚠️Warning/Dangers:
- Custom RJ-45 cables invites people to plug your ciruit into something it shouldn't
  connected to (like).
- Preferable if you can use standard wiring scheme.
- Preferable if you can label anything non-standard in an obvious way.
