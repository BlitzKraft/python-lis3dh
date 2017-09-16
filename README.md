# Modified for micropython

Written for and tested using a NodeMCU V0.9 board, with **SparkFun** LIS3DH. 

Some pin definitions are hardcoded - may potentially brick your device if run without modfication.

# python-lis3dh
Python library for using a [LIS3DH triple-axis accelerometer](https://www.adafruit.com/products/2809) on a Raspberry Pi

This is not a complete implementation of all the features of the LIS3DH - if you can help add more functionality then please contribute!

## Useful reading
 * https://www.adafruit.com/datasheets/LIS3DH.pdf
 * https://github.com/adafruit/Adafruit_LIS3DH/blob/master/Adafruit_LIS3DH.cpp
 * https://github.com/adafruit/Adafruit_LIS3DH/blob/master/Adafruit_LIS3DH.h
 * https://github.com/adafruit/Adafruit-Raspberry-Pi-Python-Code/blob/master/Adafruit_I2C/Adafruit_I2C.py
 
## Credits
 * [Matt Dyson](http://mattdyson.org) - Original implementation
 * [Mal Smalley](https://github.com/MalSmalley) - Implementation of 'click' functionality 
