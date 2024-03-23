[STM32]: <https://www.st.com/en/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus.html>
[SparkFun]: <https://www.sparkfun.com/>

## Form factors for building your solutions
<!----------------------------------------------------------------------------->

# "Breakout+ boards"
Seems like the current trend is to provide hardware components as "breakout+
boards".  The idea behind this trend appears to provide blocks that enable
makers to get up-and-running as quickly as possible. Since modern manufacturing
processes produce integrated circuits (ICs) that are too small for practical
manual assembly (and wiring up large amounts of individual pins can be tedious)
these "macro-scale" building blocks are ideal for makers.

## Microcontroller breakouts
Manufacuters even have "breakout+ boards" for microcontrollers themselves!
Though not purely breakouts in the strictest sense (they often come packaged
with supporting circuitry), most makers probably look at them in this sense.

Tehnically, the industry appears to consider them "development boards" (ex:
The Adafruit website) - likely because it is assumed larger-scale projects
use them only during the development phase before migrating to custom board
designs. Custom PCBs tend to require less manual intervention and are therefore
more robust.

On a smaller scale though: makers will likely find these boards quite adequeate
for their final product. Makers can even design their own PCBs to accept one of
these "standardized breakout+ boards".

## Castellated breakouts
Some of the newer boards like the Raspberri Pi Nano even come with castellated
mounting holes to simplify integration with custom project/PCB designs.
This way, makers only have to connect up the signals/pins you care about -
and not worry about supporting hardware & circuitry (Power delivery, access to
GPIOs, communications through USB, etc).

# Form factors (so many to choose from!)
Many organizations have come up with different form factors that are in use Today.
Since many of these designs are meant to be open, vendors often support form factors
originally developped by others.

## Adafruit:
<!----------------------------------------------------------------------------->
**Metro**: Arduino (classic)-compatible form-factor (Ada-branded)
- Big compared to what is considered practical Today.
- That said: some people will prefer the larger size - especially on the
  prototyping side of things.
- Due to their larger size: "Metro" probably qualifies more like a proper
  prototyping/development board than simple "breakout boards".
  meant to provide practical "macro-scale" breakouts (or "boardlets") for manual
  assembly of products.

Feather: One format to rule them all!
- Adafruit's attempt at making a relatively compact, standard form factor.
- Dimensions carefully chosen to strike a balance between number of available
  pins on the periphery vs space for components inside.
- By having a standard form factor & pinout, maker designs can more easily migrate
  from one microcontroller ("brain")-type to another.
- One form factor also means you only have to invest on one type of "FeatherWings"
  (expansion packs... similar to Arduino "shields")!
- Overview of the Feather line:<br>
  <https://learn.adafruit.com/adafruit-feather/feather-history>
- Features expected of Feathers:<br>
  <https://learn.adafruit.com/adafruit-feather/feathers>
- FeatherWings (add-on boards/expansion packs):<br>
  https://learn.adafruit.com/adafruit-feather/featherwings

[Trinkets](https://www.adafruit.com/category/261) (+ ItsyBitsy, Trinkey, Metro Mini, ...):
- Even smaller form factor than feather.

[Kee Boar](https://learn.adafruit.com/adafruit-kb2040):
- Designed to replace Arduino Pro Micro in making custom keyboards.
- Similar size to the ItsyBitsy - but specifically designed to be pin-compatible
  with Arduino Pro Micro boards.

**QT Py**:
- Tinyier still! Uses XIAO form-factor (Ada-branded).

Circuit Playground:
- Target STEAM learning in schools.

Gemma:
- Tiny version of Circuit Playground (it seems)! ... but for????


## Arduino
<!----------------------------------------------------------------------------->
Nano:
- Small form factor

MKR:
- ?

Classic:
- Classic form factor for a Arduino-compatible board

Mega:
- Slightly larger form factor. Typically for more powerful microcontrollers.

## Raspberry Pi:
<!----------------------------------------------------------------------------->
- RP2040 Pico: The first microcontroller board from the Raspberry Pi foundation
  <https://www.raspberrypi.com/products/raspberry-pi-pico/>

## BBC
<!----------------------------------------------------------------------------->
- **micro:bit** <https://microbit.org/>

## PJRC:
<!----------------------------------------------------------------------------->
- Teensy \*. TODO: There appears to be different form factors/versions.
- Teensy 4.0
- Teensy 4.1


## Seeed Studio:
<!----------------------------------------------------------------------------->
- XIAO: <https://www.seeedstudio.com/xiao-series-page>

## SparkFun:
<!----------------------------------------------------------------------------->
- List here

## ST-Microelectronics ([STM32]):
<!----------------------------------------------------------------------------->
- List board types here

# "Stacking" solutions
Most form factors support the option of literally "stacking on" additional
functionality on top of a base microcontroller "breakout+ board". The following
lists a few names used to brand these "stack-on" solutions:
- "shields" (Arduino)
- "wings" (Adafruit),
- "hats" (RPi)
- "bonnets" (small "hats". Pi Zero).

# Resources
<!----------------------------------------------------------------------------->
- <https://learn.adafruit.com/adafruit-feather>
- <https://www.adafruit.com/category/851>: Development platforms