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

# Development platforms
<!----------------------------------------------------------------------------->
Development platofrms provide convenient software "components" (API) to make
it easier to interact with the hardware components. Ideally/typically, the API
is written such that all hardware interactions require similar glue code.

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
- **`CircuitPython` platform** ([CktPy]/[Docs][CktPy-Docs]/[Download][CktPy-Download]):
  A fork (derivative) of MicroPython [Adafruit][Adafruit-Learn]. Tries to
  extend MicroPython to improve on ease-of-use. Some aspects are not quite
  interoperable with native Micropython API/solutions.


## Resources
- <https://learn.adafruit.com/welcome-to-circuitpython/what-is-circuitpython>