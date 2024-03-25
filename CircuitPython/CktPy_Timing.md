## CircuitPython: Timing

# Ways to measure passage of time
- [`time.monotonic()`](https://docs.circuitpython.org/en/latest/shared-bindings/time/index.html#time.monotonic):
  - ✔️ standard python
  - ❌️ Returns seconds as `float` (most microcontrollers don't have FPU).
- [`time.monotonic_ns()`](https://docs.circuitpython.org/en/latest/shared-bindings/time/index.html#time.monotonic_ns):
  - ✔️ standard python
  - Returns `int` representing time in ns.
  - ❌️ \"Not available on boards without long integer support.\"
- [`supervisor.ticks_ms()`](https://docs.circuitpython.org/en/latest/shared-bindings/supervisor/index.html#supervisor.ticks_ms):
  - Returns `int` representing time in ms.
  - ❌️ NOT standard python... but neither are most of libs in CircuitPython bundle.
- [`adafruit_ticks.ticks_ms()`](https://docs.circuitpython.org/projects/ticks/en/stable/api.html):
  - Returns `int` representing time in ms.
  - ❌️ Need to install lib.
  - ❔ Not sure what it adds beyond `supervisor.ticks_ms()`.
