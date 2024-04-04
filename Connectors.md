<!-- Reference-style links to make tables & lists more readable -->
[VCELiNK-Keystone]: <https://www.amazon.ca/stores/page/76F89957-8DA8-4230-91C8-5E17D49C24AA>
[PrimeCables-KeystoneAV]: <https://www.primecables.ca/c-1089-audio-video-keystone-jacks>
[InfiniteCables-SurfaceBox]: <https://www.infinitecables.com/collections/surface-boxes>

## Connectors

# Breadboard/protoboard wiring
<!----------------------------------------------------------------------------->
Standard breadboards use 22 AWG (solid-core) "hook-up" wires to connect-up
circuits elements together:
- 6 spools: <https://www.adafruit.com/product/1311>
- 10 spools: <https://www.adafruit.com/product/3174>

# Dupont cables: the next step up:
<!----------------------------------------------------------------------------->
It seems like the next step up from using 22AWG cables on breadboards is to use
cables terminated with "Dupont connectors".

Pre-made Dupont "jumper wires":
- Adafruit selection: <https://www.adafruit.com/category/306>
- Adafruit starter kit: <https://www.adafruit.com/product/5070>

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
- [ADA/STEMMA (classic) device](https://www.adafruit.com/category/1019):
  Analog/Digital/PWM device (not I2C).
- Used to connect with breakout boards of simple blocks like motors & neo-pixel products.
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
  connected to (ex: your PC's ethernet jack).
- Preferable to use standard wiring scheme whenever possible.
- Preferable to label anything non-standard in an obvious way.

## Connectors Tools:
⚠️Warning:
- There is a dizzying number of different crimping tools that work with
  different types of connector ends.
- Information on which are which crimping tools works well with which connector
  appears to be misleading, sparse and/or difficult to find.
- Not sure why finding a matching tool for a given connector type is so
  difficult - especially given that makers mostly stick to a finite subset of
  the same connectors.

Example of some crimpers... just not sure which ones work:
- "Universal" Crimpers: (Adafruit): <https://www.adafruit.com/category/622>

I personally tried the SN-28B tool (typ. blue handles). I would say no one die
is the right size for any of the JST connectors mentionned here (physically too
large/long). Also: it does not include a single "round"/"O" die - which is
apparently a requirement for crimping Dupont connectors. So I am still lost
when it comes to the intended purpose of the SN-28B tool (what does it crimp?)
given how popular it appears to be.

### Searching for compatible tools
Here, I list some information that seems to point to what is needed to
crimp these small connectors:
- <https://cdn-shop.adafruit.com/datasheets/JST_CrinpChart%20%28English%29.pdf>
- <https://www.engineertools-jp.com/pa24>
  - [Direct link to JST "Application chart"](https://www.nejisaurus.engineer.jp/_files/ugd/104650_594335d26d724883affcaa8929df7c19.pdf)
  - [Talks about "M" vs "O"-shaped dice](https://www.youtube.com/watch?v=tSq1LYbP0KA)
- <https://www.youtube.com/watch?v=ltEFDEAx_yA>

The information collected skews towards the PA-24 pliers. Not sure if that is red herring.