# AZSMZ-TFT
## Weather station Open source 
[OpenWeatherMap](weatherstation/OpenWeatherMap)     
[YahooApi](weatherstation/YahooApi)  

## Where to get:
## http://bancuit.aliexpress.com 
## http://azsmz.aliexpress.com  

![AZSMZ TFT](resources/AZSMZ-11.jpg)

## Install-Instructions:  ##
https://github.com/cxandy/esp8266-weather-station-color/wiki/Install-Instructions    

pin config:    
TOUCH_CS = 5;
TOUCH_IRQ = 4;
BTN_1 = 0;
 
Board Ver 1.6 - 1.8    
  TFT_DC = 0;
  TFT_CS = 2;
  SD_CS = 15;
 
Board Ver 1.9    
  TFT_DC = 0;
  TFT_CS = 15;
  SD_CS = 2;

## Flash new firmware (so easy) ##
[Follow me](resources/Flash.md)

## Long press "Flash" button to enter web Configuration at running.  ##
## Short press "Flash" button to reset config In a few seconds after restart. ##

The image below For use DHT11:      
![AZSMZ TFT TOUCH](resources/DHT11-WIRE.jpg)

The image below For AZSMZ TFT TOUCH Ver1.8:
![AZSMZ TFT TOUCH](resources/AZSMZ-TFT-TOUCH-1.8-WIRE.jpg)

The image below For AZSMZ TFT TOUCH Ver1.6 & Ver1.61:
![AZSMZ TFT TOUCH](resources/AZSMZ-TFT-TOUCH-WIRE.jpg)

## Software Requirements/ Libraries
 * Mini Grafx by Daniel Eichhorn
 * ESP8266 WeatherStation by Daniel Eichhorn
 * Json Streaming Parser by Daniel Eichhorn
 * simpleDSTadjust by neptune2

## Settings
Please have a good look at the settings.h file. There you can:
 * set your location for the weather information
 * Set the clock mode: 12hour (am/pm) or 24hour mode
 * Metric system for temperature
 * Timezone and daytime saving options
 * API key



