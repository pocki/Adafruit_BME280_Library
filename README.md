Adafruit BME280 Particle Library
================================

This is a library for the SparkFun BME280 Humidity, Barometric Pressure + Temp sensor

Particle Photon, Core & Electorn DHT Library based on Arduino Library for BME280 sensors adapted by Markus Haack

Works with the following BME280-Breakouts as well:
 * http://www.watterott.com/en/BME280-Breakout-humidity-pressure-temperature-sensor
 * http://www.adafruit.com/products/2652

These sensors use I2C or SPI to communicate, up to 4 pins are required to interface.

This library allows the user to:

* Read pressure in Pa
* Read temperature in C & F
* Read humidity in %RH
* Read temperature in F
* Read altitude in meters
* Read altitude in feet

Repository Contents
-------------------

* **/examples** - Example sketches for the library (.ino). Run these from the Arduino IDE. 
* **/src** - Source files for the library (.cpp, .h).
* **library.properties** - General library properties for the Particle and Arduino package manager. 

Version History
---------------
* [V_1.0.0](https://github.com/mhaack/Adafruit_BME280_Library/releases/tag/1.0.0) - September 2015 Initial Release
* [V_1.0.4](https://github.com/mhaack/Adafruit_BME280_Library/releases/tag/1.0.4.particle) - October 2015 pull from Adafruit repo to support multiple sensors with different calibration values
* [V_1.1.2](https://github.com/mhaack/Adafruit_BME280_Library/releases/tag/1.1.2.particle) - January 2017 migrated to V2 library, pulled minor changes

License Information
-------------------

Original Arduino library: https://github.com/adafruit/Adafruit_BME280_Library

Adafruit invests time and resources providing this open source code,
please support Adafruit and open-source hardware by purchasing
products from Adafruit!

Check out the links above for our tutorials and wiring diagrams

Written by Limor Fried/Ladyada for Adafruit Industries.  
BSD license, all text above must be included in any redistribution
