# Adafruit ILI9341 Arduino Library - Seeed Studio TFT Fork

#### This is a fork to enable default functionality for the [2.8" TFT Touch Shield v2.0](http://wiki.seeedstudio.com/2.8inch_TFT_Touch_Shield_v2.0/)

Use by instantiating the class with:

```c++
Adafruit_ILI9341 tft = Adafruit_ILI9341();
```

That's it.  No specific pins you need to specify.  If you look at the header file, you'll see that pins `5` and `6` are hardcoded into the constructor that takes no arguments.

---

This is a library for the Adafruit ILI9341 display products

This library works with the Adafruit 2.8" Touch Shield V2 (SPI)
  * http://www.adafruit.com/products/1651

Adafruit 2.4" TFT LCD with Touchscreen Breakout w/MicroSD Socket - ILI9341
  * https://www.adafruit.com/product/2478

2.8" TFT LCD with Touchscreen Breakout Board w/MicroSD Socket - ILI9341
  * https://www.adafruit.com/product/1770

2.2" 18-bit color TFT LCD display with microSD card breakout - ILI9340
  * https://www.adafruit.com/product/1480

TFT FeatherWing - 2.4" 320x240 Touchscreen For All Feathers 
  * https://www.adafruit.com/product/3315

Check out the links above for our tutorials and wiring diagrams.
These displays use SPI to communicate, 4 or 5 pins are required
to interface (RST is optional).

Adafruit invests time and resources providing this open source code,
please support Adafruit and open-source hardware by purchasing
products from Adafruit!

Written by Limor Fried/Ladyada for Adafruit Industries.
MIT license, all text above must be included in any redistribution

To download. click the DOWNLOADS button in the top right corner, rename the uncompressed folder Adafruit_ILI9341. Check that the Adafruit_ILI9341 folder contains Adafruit_ILI9341.cpp and Adafruit_ILI9341.

Place the Adafruit_ILI9341 library folder your arduinosketchfolder/libraries/ folder. You may need to create the libraries subfolder if its your first library. Restart the IDE

Also requires the Adafruit_GFX library for Arduino.
