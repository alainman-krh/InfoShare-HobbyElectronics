[CktPy]: <https://circuitpython.org/>
[CktPy-Docs]: <https://docs.circuitpython.org>
[uPy]: <https://docs.micropython.org>
[uPy-Docs]: <https://micropython.org/>
[Arduino]: <https://www.arduino.cc/>
[Adafruit-Learn]: <https://learn.adafruit.com/>

# Development platforms
<!----------------------------------------------------------------------------->
Development platofrms provide convenient software "components" (API) to make
it easier to interact with the hardware components. Ideally/typically, the API
is written such that all hardware interactions require similar glue code.

Here are some the more popular development platforms at this time:
- **[Arduino] platform**: C++ programming. Runs very fast, uses little memory. C++ is more
  difficult to master - although simpler Arduino sketches (DEFINE/better word)
  are fairly easy to understand.
- **`MicroPython` platform** ([uPy]): Efficient (small+fast) Python implementation targeting
  microcontroller platforms. Python is typically slower than C++, and requires
  more memory to both store programs, and run. That said: programming in python
  is much faster, and the learning curve is not nearly as steep.
- **`CircuitPython` platform** ([CktPy]): A fork (derivative) of MicroPython [Adafruit][Adafruit-Learn].
  Tries to extend MicroPython to improve on ease-of-use. Some aspects are not quite
  interoperable with native Micropython API/solutions.


## Resources
- <https://learn.adafruit.com/welcome-to-circuitpython/what-is-circuitpython>