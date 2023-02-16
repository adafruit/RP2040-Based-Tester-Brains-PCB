## Adafruit RP2040 Based Tester Brains PCB

<img src="assets/0.jpg?raw=true" width="500px">

PCB files for the Adafruit RP2040 Based Tester Brains. 

Format is EagleCAD schematic and board layout

### Description

This board is what we use internally at Adafruit to program and test boards with microcontrollers on them. An [RP2040 Pico](https://www.adafruit.com/product/5525) (or perhaps PicoW?) is used to run the test software. [Use a 16x2 LCD (ideally RGB backlight)](https://www.adafruit.com/product/398)( for display output with color feedback such as green for pass, red for fail. Firmware files can be stored on MicroSD card which is slotted in. Connect the right hand side to the device-under-test jig which can be different for each product. [USB Host testing is done with bitbang PIO support in TinyUSB!](https://github.com/adafruit/Adafruit_TinyUSB_Arduino) The RP2040 can also perform ESP32 programming, RP2040-via-USB, AVR ICSP/UPDI, or SWD DAP. [See the TestBed library for some examples.](https://github.com/adafruit/Adafruit_TestBed)

**THIS IS NOT AN ADAFRUIT PRODUCT, IT IS COMPLETELY AND UTTERLY UNSUPPORTED. DO NOT ASK FOR SUPPORT OR ASSISTANCE, WE DON'T GUARANTEE IT WORKS FOR YOU OR AT ALL AND ARE ONLY PUBLISHING IT IN THE HOPES THAT IT IS USEFUL FOR SOMEONE!**

[![rp2040 programming an rp2040 ~ flash inception](https://img.youtube.com/vi/sjl7aVK2Q2U/0.jpg)](https://www.youtube.com/watch?v=sjl7aVK2Q2U)

[![The Desk of Ladyada - RP2040 Tester bringup & LCD QT revisions](https://img.youtube.com/vi/3gakI1QBvXw/0.jpg)](https://www.youtube.com/watch?v=3gakI1QBvXw)

[![Desk of Ladyada - Teensy Tester Redesigned to RP2040 Pico](https://img.youtube.com/vi/iSWNARXhVM0/0.jpg)](https://www.youtube.com/live/iSWNARXhVM0?feature=share&t=951)

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
