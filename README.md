# TFT_Touch
Arduino touch screen library for XPT2046

This library has been tested on a 2.4" TFT screen that uses
the ILI9341 display driver and XPT2046 touch controller.

These displays are available at low cost on eBay and AliExpress.

The library includes two sketches:

    * TFT_Touch_Calibrate: to calibrate and test the screen
    * TFT_Touch_Draw_2-4 : a simple paint program

To make things really easy the claibration sketch reports the setup()
calibration code to use in your sketch via a serial port message.

The library could be used with any graphics library but the examples
use this one:

https://github.com/Bodmer/TFT_ILI9341


