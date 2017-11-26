# onion_omega
Tests with using the onion.io omega chip

## The MS5803 pressure chip

The chip is a pressure and temperature chip communicating over I2C bus usually starts at adress 0x76
I used the software from https://github.com/ControlEverythingCommunity/MS5803-14BA/blob/master/Python/MS5803_14BA.py as a base for the example enclosed

A sensor data sheet can be found here https://s3.amazonaws.com/controleverything.media/controleverything/Production%20Run%206/43_MS5803-30BA_I2CS/Datasheets/MS5803-30BA.pdf

## The Grove LCD

the grovesensor serie is very easy to use and a favorite for me to do tests on but it's mainly used with raspberries
I used the code from https://github.com/DexterInd/GrovePi/blob/master/Software/Python/grove_rgb_lcd/example.py
I made a wrapper class to keep the syntax from grovePI projekt 

## the onion I2C library
the onion library fnuncations fro I2C can be found here https://wiki.onion.io/Documentation/Libraries/I2C-Python-Module 
