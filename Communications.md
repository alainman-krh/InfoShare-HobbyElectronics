<!-- Reference-style links to make tables & lists more readable -->
[I2C-Wiki]: <https://en.wikipedia.org/wiki/I%C2%B2C>
[SPI-Wiki]: <https://en.wikipedia.org/wiki/Serial_Peripheral_Interface>
[UART-Wiki]: <https://en.wikipedia.org/wiki/Universal_asynchronous_receiver-transmitter>

## Communications/Wi-Fi/Bluetooth

# Wired protocols
<!----------------------------------------------------------------------------->
Modern microcontrollers typically have built-in support for at least 3 protocols:
- **I2C**: Lightweight "two-wire" (SDA/SCL) synchronous inter-chip communication.
  - Technically require routing of supply/ground as well.
  - [Wikipedia: I2C][I2C-Wiki]
  - [Digikey: CircuitPython Basics I2C and SPI](https://www.digikey.ca/en/maker/projects/circuitpython-basics-i2c-and-spi/9799e0554de14af3850975dfb0174ae3)
  - [Adafruit: I2C -- in CircuitPython](https://learn.adafruit.com/circuitpython-essentials/circuitpython-i2c)
  - [Adafruit: CircuitPython I2C and SPI Under the Hood](https://learn.adafruit.com/circuitpython-basics-i2c-and-spi)
- **Serial Peripheral Interface (SPI)**: Synchronous 4+ wire interface for inter-chip communication.
  - [Wikipedia: Serial Peripheral Interface][SPI-Wiki]
  - [Digikey: CircuitPython Basics I2C and SPI](https://www.digikey.ca/en/maker/projects/circuitpython-basics-i2c-and-spi/9799e0554de14af3850975dfb0174ae3)
  - [Adafruit: CircuitPython I2C and SPI Under the Hood](https://learn.adafruit.com/circuitpython-basics-i2c-and-spi)
- **Universal Asynchronous Receiver-Transmitter (UART)**: Asynchronous serial communication.
  - [Wikipedia: UART][UART-Wiki]

But other common protocols exist -- and can be integrated into your maker solutions.

## UART: universal asynchronous receiver / transmitter [Wikipedia][UART-Wiki]
A circuit able to implement asynchronous communication protocols of various
configurations.

For proper communcation, the UART must be configured to match the protocol of the
attached circuit(s)/device(s):
- Speed (baud rate): (ex: 9600, 115200, ...)
- \# data bits: 4-8
- \# stop bits: 1/1.5/2
- Parity: None/Even/Odd/Mark/Space
- Flow Control: None/Hardware/Xon/Xoff

But also needs to operate on a matching electrical standard like RS-232, RS-422, RS484 (below).

<a name="EIA_TIA_standards"></a>
## EIA/TIA electrical standards
3 well established electrical standards are defined by both the TIA and EIA:
- [RS-232 (Also EIA-232 or TIA-232)](https://en.wikipedia.org/wiki/RS-232)
- [RS-422 (Also EIA-422 or TIA-422)](https://en.wikipedia.org/wiki/RS-422)
- [RS-485 (Also: EIA-485 or TIA-485)](https://en.wikipedia.org/wiki/RS-485)

Links to info on TIA/EIA:
- [Telecommunications Industry Association (TIA)](https://en.wikipedia.org/wiki/Telecommunications_Industry_Association)
- [Electronic Industries Alliance (EIA)](https://en.wikipedia.org/wiki/Electronic_Industries_Alliance)

These standards define the electrical characteristics of a communications link
...but not the signalling protocol itself. That part is typically left up to
the UART block (though could be implemented by another block).

## CAN
Can bus started out in the automotive industry. Its capabilities are similar
to what can be achieved with RS-485, but has a more resilient protocol
(actually, unlike RS-485: it actually defines a signalling protocol - and not
just an electrical standard).

Resources:
- <https://www.influxbigdata.in/post/can-bus-vs-rs485-3-reasons-why-can-is-better>
- <https://www.maximintegrated.com/content/dam/files/design/technical-documents/white-papers/can-wp.pdf>

## Comparison Table
TODO: Make Table

NOTE: Differential protocols are less succeptible to noise, and thus typically
more robust.


# Wireless protocols
<!----------------------------------------------------------------------------->
TODO: Make Table

(Ranges using info from Adafruit):
- Bluetooth (classic), Bluetooth Low Energy (LE): ~10m range
- Wi-Fi: ~100m range
- ZigBee: ~100m range
- LoRa: ~2km (basic antennae), ~20km (directional antennae)
- Packet Radio (RFM69): ~500m range (basic antennae). ~5km range (directional antennae)
- Cellular

Some more description:
- Bluetooth: <https://learn.adafruit.com/adafruit-feather/bluetooth-feathers>
- LoRa/RFM69: <https://learn.adafruit.com/adafruit-feather/lora-radio-feathers>
- ONLY ESP32 can do BT classic in Adafruit's lineup.