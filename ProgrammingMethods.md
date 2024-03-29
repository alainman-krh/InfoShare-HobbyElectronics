## Programming methods (uploading code)
<!----------------------------------------------------------------------------->

# Brief History
<https://learn.adafruit.com/bootloader-basics/a-brief-history-of-bootloading>

# Bootloaders: Today's convenience
<!----------------------------------------------------------------------------->

Basic bootloader (ex: serial/over-USB):
- <https://learn.adafruit.com/bootloader-basics/types-of-bootloaders#basic-bootloaders-3030121>

Advanced bootloaders (ex: UF2):
- <https://learn.adafruit.com/bootloader-basics/types-of-bootloaders#advanced-bootloaders-3030122>

# More programmers (A deeper dive)
Look into AVR, ISP, UPDI, JTAG, PDI, and TPI:
- <https://www.kanda.com/blog/microcontrollers/all-you-need-to-know-about-avr-isp-updi-jtag-pdi-and-tpi/>

AVR vs FTDI programmer:
- <https://learn.adafruit.com/ftdi-friend/ftdi-friend-vs-avr-programmer>
- TLDR: AVR programs a blank chip (might write a bootloader) - and FTDI provides a serial link to feed data to bootloader.
- But... can also write a blank chip (slowly) with some effort [(read here)](https://learn.adafruit.com/ftdi-friend/programming-blank-avrs).