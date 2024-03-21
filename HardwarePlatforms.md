[STM32]: <https://www.st.com/en/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus.html>
[SparkFun]: <https://www.sparkfun.com/>

# Form factors (so many to choose from!)
<!----------------------------------------------------------------------------->
...Where to start?

Microcontrollers are often packaged into what are called "development boards".
The idea with these boards is to quickly get up-and-running without having to
worry about much of the supporting circuitry (Power delivery, access to GPIOs,
communications through USB, etc).

> Talk about more than dev board. Breakouts are "macro-scale" building-blocks for makers.
Most ICs now are too small for manuiplation by hand. Assembled by pick/place machines.
Electronics manufacturing works best at large volumes.

...So it is practical for us as makers to think about these solutions, not only
as "development boards", but also "building blocks", or modules that are ready for assembly.

Many companies below support form factors originally developped by others.

Most of the form factors listed below can be better adapted to a prototyping by
purchasing corresponding "shields" (Arduino terminology), "wings" (Ada term),
"hats" (RPi term), "bonnets" (small hats), etc. These effectively
convert board from a "microcontroller mdule" into a proper development board
(at least, in terms of what most makers likely see things).


<!----------------------------------------------------------------------------->
Adafruit:
- Metro: Arduino (classic)-compatible form-factor (Ada-branded). They are big
  compared to what is considered practical Today. That said: some people will
  prefer the larger size - especially on the prototyping side of things.
  I would say the Metro is more of a prototyping board than a "hardware platform"
  meant to provide practical "macro-scale" breakouts (or "boardlets") for manual
  assembly of products.
- Feather: One format to rule them all! Adafruit's attempt at making a standard
  form factor by carefully choosing dimensions that strikes a nice balance
  between number of pins available on the outside (+ space for components inside),
  while keeping things small overall! By keeping a standard formfactor & pinout,
  your design can more easily migrate from one microcontroller ("brain")-type to
  another. It also means you only have to invest on one type of shields (expansion packs)!
  - Overview of the Feather line: <https://learn.adafruit.com/adafruit-feather/feather-history>
  - Features expected of Feathers: <https://learn.adafruit.com/adafruit-feather/feathers>
- [Trinkets](https://www.adafruit.com/category/261) (+ ItsyBitsy, Trinkey, Metro Mini, ...):
  Even smaller form factor than feather.
- Kee Boar: <https://learn.adafruit.com/adafruit-kb2040> Designed to replace Arduino Pro Micro
  in making custom keyboards. Similar size to the ItsyBitsy - but specifically
  designed to be pin-compatible with Arduino Pro Micro boards.
- **QT Py**: Tinyier still! Uses XIAO form-factor (Ada-branded).
- Circuit Playground: Target STEAM learning in schools.
- Gemma: Tiny! ... but for????
(There are many!)

Arduino
- Nano: Small form factor
- MKR:
- Classic:
- Mega:

Raspberry Pi:
- RP2040 Pico: The first microcontroller board from the Raspberry Pi foundation
  <https://www.raspberrypi.com/products/raspberry-pi-pico/>

BBC
- **micro:bit** <https://microbit.org/>

PJRC:
- Teensy \*. TODO: There appears to be different form factors/versions.
- Teensy 4.0
- Teensy 4.1


Seeed Studio:
- XIAO: <https://www.seeedstudio.com/xiao-series-page>

SparkFun:
- List here

ST-Microelectronics ([STM32]):
- List board types here

## Resources
<!----------------------------------------------------------------------------->
- <https://learn.adafruit.com/adafruit-feather>
- <https://www.adafruit.com/category/851>: Development platforms