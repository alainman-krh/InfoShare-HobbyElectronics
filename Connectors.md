
## Connectors

# Maker power/communications:
This section lists connectors popular with current maker boards, and their
application. More information can be found here:
- <https://learn.adafruit.com/introducing-adafruit-stemma-qt/stemma-qt-comparison>

⚠️Warning
- Not all devices expect the same signal levels/power to be delivered on their
  connectors. Typical operating voltages in use at the time of writing are 5V
  and 3.3V. Please ensure proper level match/shifting is in order.
- Not all formats work together. Please refer to:<br>
  <https://learn.adafruit.com/introducing-adafruit-stemma-qt/stemma-qt-comparison#quick-comparison-3035247>

## JST-PH (2mm/Small)
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

