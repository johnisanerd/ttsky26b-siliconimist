<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Chip1 - Hello World

https://wokwi.com/projects/463082608110406657

Input connects to the 8 switch dip switch.  (https://docs.wokwi.com/parts/wokwi-dip-switch-8)
Output Design connects to the LCD 7-segment display.  (https://docs.wokwi.com/parts/wokwi-7segment)
Switches 1-4 are inverted and turn off when they should turn on.  

## How to test

|Inputs | Outputs |
|--------|--------|
|00000000|11110000|
|10000000|01110000|
|11000000|00110000|
|11100000|00010000|
|11110000|00000000|
|11111000|00001000|
|11111100|00001100|
|11111110|00001110|
|11111111|00001111|

## External hardware

- 8 switch dip switch.  (https://docs.wokwi.com/parts/wokwi-dip-switch-8)
- LCD 7-segment display.  (https://docs.wokwi.com/parts/wokwi-7segment)
