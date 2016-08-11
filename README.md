MEEPROMMER
==========

__Note: This version has been modified to use smaller serial buffers to work better with cheap CH340G-based Arduino clones.__
The Arduino bootloader was also modified to increase its serial buffers using this guide: http://folk.uio.no/jeanra/Microelectronics/CustomSizeArduinoBuffer.html

EEPROM programmer based on Arduino hardware

The MEEPROMMER is a combination of hardware and software that lets you read and write 
data from (and to) 28Cxxx EEPROMS.

At the moment we have a working prototype on a PCB that uses an Arduino Nano and an 
Arduino-shield that can directly plugged to an Arduino Uno. 

The Arduino firmware provides a serial interface with simple commands to transfer data 
between a host computer and an EEPROM.

For the host computer a Java based GUI application is available that uses the RxTx 
library to interface the programmer. There is also a command line client written in python available.
