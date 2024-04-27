<!-- Reference-style links to make tables & lists more readable -->
[CktPy]: <https://circuitpython.org/>
[CktPy-Docs]: <https://docs.circuitpython.org>
[CktPy-Download]: <https://circuitpython.org/downloads>
[uPy]: <https://micropython.org/>
[uPy-Docs]: <https://docs.micropython.org>
[uPy-Download]: <https://micropython.org/download/>
[Arduino]: <https://www.arduino.cc/>
[Arduino-Docs]: <https://docs.arduino.cc/>
[Arduino-Download]: <https://www.arduino.cc/en/software>
[Adafruit-Learn]: <https://learn.adafruit.com/>
[Blinka-Home]: <https://circuitpython.org/blinka>
[Blinka-Docs]: <https://docs.circuitpython.org/projects/blinka/en/latest/>

## Development platforms
<!----------------------------------------------------------------------------->
Development platofrms provide convenient software "components" (API) to make
it easier to interact with the hardware components. Ideally/typically, the API
is written such that all hardware interactions require similar glue code.

# Popular platforms
Here are some the more popular development platforms at this time:
- **[Arduino] platform** ([Docs][Arduino-Docs]/[Download][Arduino-Download]):
  C++ programming. Runs very fast, uses little memory. C++ is more difficult to
  master - although simpler Arduino sketches (DEFINE/better word) are fairly
  easy to understand.
- **`MicroPython` platform** ([uPy]/[Docs][uPy-Docs]/[Download][uPy-Download]):
  Efficient (small+fast) Python implementation targeting microcontroller
  platforms. Python is typically slower than C++, and requires more memory to
  both store programs, and run. That said: programming in python is noticeably
  faster, and the learning curve is not nearly as steep.
  - [Maximising MicroPython speed](https://docs.micropython.org/en/latest/reference/speed_python.html)
  - [Optimizations](https://docs.micropython.org/en/latest/develop/optimizations.html)
- **`CircuitPython` platform** ([CktPy]/[Docs][CktPy-Docs]/[Download][CktPy-Download]):
  A fork (derivative) of MicroPython [Adafruit][Adafruit-Learn]. Tries to
  extend MicroPython to improve on ease-of-use. Some aspects are not quite
  interoperable with native Micropython API/solutions.
  - \*Pre-compiled [Library Bundles](https://circuitpython.org/libraries) are also available for CircuitPython.
  - At time of writing: Does not include multi-core support (unlike MicroPython).
  - [Adafruit: What is CircuitPython?](https://learn.adafruit.com/welcome-to-circuitpython/what-is-circuitpython)
  - [Adafruit: Welcome to CircuitPython! (FAQ)](https://learn.adafruit.com/welcome-to-circuitpython/frequently-asked-questions)
  - [Adafruit: CircuitPython Essentials](https://learn.adafruit.com/circuitpython-essentials)
  
# Blinka libraries
Making CircuitPython libraries available to SBCs (ex: Raspberry Pi) and MicroPython itself!
- [Blinka-Home], [Blinka-Docs]
- [Adafruit: CircuitPython Libraries on Linux and Raspberry Pi](https://learn.adafruit.com/circuitpython-on-raspberrypi-linux)
- [Adafruit: Adding a Single Board Computer to Blinka](https://learn.adafruit.com/adding-a-single-board-computer-to-blinka)

# Other resources
- [🎞️ CircuitPython vs MicroPython: Key Differences](https://www.youtube.com/watch?v=wyOcb2MHzIs)