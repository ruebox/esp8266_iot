# Chirp I2C soil moisture sensor 
This readme describe how to setup and use the chirp standalone sensor with NodeMCU.
This sensor is a capacitive soil moisture sensor similar to Vegetronix VH400, but with digital i2c interface and of lower price.

* [Chirp! - the plant watering alarm](https://wemakethings.net/chirp/): capacitive soil moisture sensor. Original page incl. history and prototypes 
* [Chirp!@tindie](https://www.tindie.com/products/miceuz/chirp-plant-watering-alarm/): Where to buy 
* [I2C Soil moisture sensor](https://www.tindie.com/products/miceuz/i2c-soil-moisture-sensor/): Based on Chirp!, but as standalone realization with I2C interface.

##Requirements:
* I2C Soil moisture sensor (v2.7.5)
* Micropython for esp8266
    * (Download)[http://micropython.org/download#esp8266] e.g. esp8266-20170612-v1.9.1.bin
    * Note: With older versions of micropython I was not able to successfully read I2C registers.
    * (Tutorial)[https://docs.micropython.org/en/latest/esp8266/esp8266/tutorial/intro.html]: Who to get started with micropython on esp8266


##Layout of breadboard



##Deploy to esp8266

