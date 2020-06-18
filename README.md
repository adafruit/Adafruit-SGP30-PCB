## Adafruit SGP30 Air Quality Sensor PCB

<a href="http://www.adafruit.com/products/3709"><img src="assets/3709.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit SGP30 Air Quality Sensor. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/3709

### Description

Breathe easy with the SGP30 Multi-Pixel Gas Sensor, a fully integrated MOX gas sensor. This is a very fine air quality sensor from the sensor experts at Sensirion, with I2C interfacing and fully calibrated output signals with a typical accuracy of 15% within measured values. The SGP combines multiple metal-oxide sensing elements on one chip to provide more detailed air quality signals.

This is a gas sensor that can detect a wide range of Volatile Organic Compounds (VOCs) and H2 and is intended for indoor air quality monitoring. When connected to your microcontroller (running our library code) it will return a Total Volatile Organic Compound (TVOC) reading and an equivalent carbon dioxide reading (eCO2) over I2C.

The SGP30 has a 'standard' hot-plate MOX sensor, as well as a small microcontroller that controls power to the plate, reads the analog voltage, tracks the baseline calibration, calculates TVOC and eCO2 values, and provides an I2C interface to read from. Unlike the CCS811, this sensor does not require I2C clock stretching.

This part will measure eCO2 (equivalent calculated carbon-dioxide) concentration within a range of 400 to 60,000 parts per million (ppm), and TVOC (Total Volatile Organic Compound) concentration within a range of 0 to 60,000 parts per billion (ppb).

Please note, this sensor, like all VOC/gas sensors, has variability and to get precise measurements you will want to calibrate it against known sources! That said, for general environmental sensors, it will give you a good idea of trends and comparison. The SGP30 does have built in calibration capabilities, note that eCO2 is calculated based on H2 concentration, it is not a 'true' CO2 sensor for laboratory use.

Another nice element to this sensor is the ability to set humidity compensation for better accuracy. An external humidity sensor is required and then the RH% is written over I2C to the sensor, so it can better calculate the TVOC/eCO2 values.

For your convenience we've pick-and-placed the sensor on a PCB with a 1.8V regulator and some level shifting so it can be easily used with your favorite 3.3V or 5V microcontroller.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Kevin (KTOWN) Townsend for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
