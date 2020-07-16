Adafruit_SH1106
===============

Cloned https://github.com/wonho-maker/Adafruit_SH1106
Made it compile/work for ESP32 boards. So I could switch from Adafruit_SSD1306 library directly to this without huge code changes.
Beware that for some reason this SH1106 library is 4x slower than current SSD1306 library. Maybe its the SH1106 chip itself.

Description
===========

Adafruit graphic library for SH1106 driver lcds.

some small oled lcd use SH1106 driver.

I change the adafruit SSD1306 to SH1106 

SH1106 driver similar to SSD1306. thus, just change the display() method. 
 
However, SH1106 driver don't provide several functions such as scroll commands.


 Adafruit-GFX-Library
 https://github.com/adafruit/Adafruit-GFX-Library
