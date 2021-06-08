# Avalanche keyboard

Avalanche keyboard is an ergonomic split keyboard with 4x6 (or 3x6 if you break off the 'digits' row) column staggered keys,
5 thumb keys, 1 key for pinky (break off-able too) and 1 additional key for index finger (62 keys total). QMK firmware for Avalanche is [here](https://github.com/vlkv/qmk_firmware/tree/master/keyboards/avalanche).

Avalanche design was inspired by a number of great keyboards. You may read more about it
[in my reddit post](https://www.reddit.com/r/MechanicalKeyboards/comments/mkwddp/introducing_the_avalanche_yet_another_one_ergo/).


![Avalanche v1.0 First Build](/images/avalanche_v2-0.jpg)


## Layout tester

Cut [left half](https://github.com/vlkv/avalanche_info/blob/master/layout_tester/Avalanche_v2_0_left_A4.pdf) and
[right half](https://github.com/vlkv/avalanche_info/blob/master/layout_tester/Avalanche_v2_0_right_A4.pdf)
from some piece of a cardboard, insert switches, put on the keycaps and try the layout.


## Support the project

I have spend many hours, efforts and money designing and building prototypes of the Avalanche. If you like the board
and you want to thank the creator you may:
* Become a patron [at Patreon](https://www.patreon.com/vitvlkv).
* Donate via PayPal [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=99MYK4CNR8DP2).


## Gerber files

* Version 2.0
  * [PCB](https://github.com/vlkv/avalanche/blob/v2.0/pcb/Gerbers_pcb.zip)
  * [Top plate](https://github.com/vlkv/avalanche/blob/v2.0/plate_top/Gerbers_plate_top.zip)
  * [Bottom plate](https://github.com/vlkv/avalanche/blob/v2.0/plate_bottom/Gerbers_plate_bottom.zip)
  * TODO: Add ProMicro/OLED cover gerber files...

## Release notes
Are [here](https://github.com/vlkv/avalanche/blob/master/release_notes.md).

## Parts list

| #  | Name                          | Quantity | Example URL                                           |
|----|-------------------------------|----------|-------------------------------------------------------|
| 1  | PCB                           | 2        | |
| 2  | Top plate                     | 2        | |
| 3  | Bottom plate                  | 2        | |
| 4  | ProMicro (ATmega32U4 5V/16MHz)| 2        | https://aliexpress.ru/item/2010847161.html            |
| 5  | Sockets for ProMicro 3.5mm    | 2        | https://aliexpress.ru/item/32360715483.html           |
| 6  | Kailh hotswap sockets         | 64       | https://aliexpress.ru/item/32903471019.html           |
| 7  | Diode 1N4148 (SMD or through hole)  | 64       | https://aliexpress.ru/item/32881432301.html |
| 8  | TRRS sockets PJ320A                 | 2        | https://aliexpress.ru/item/32368285821.html |
| 9  | TRRS Cable (straight connectors)    | 1        |  |
| 10 | Reset button (DIP switch)           | 2        | https://aliexpress.ru/item/4000209910403.html |
| 11 | Bumpons for bottom plate (set)      | 1        | https://aliexpress.ru/item/32912066603.html or https://aliexpress.ru/item/32680543746.html |
| 12 | M2 screws 3mm                       | 18       | https://aliexpress.ru/item/32976056190.html |
| 13 | M2 standoffs 3mm                    | 18       | https://aliexpress.ru/item/32597776358.html |
| 14 | Rotary encoder                      | 2        | https://aliexpress.ru/item/32976046900.html |
| 15 | Knob (for rotary encoders)          | 2        | https://www.aliexpress.com/item/33004945608.html |
| 16 | Keyboard switch (Cherry-MX compatible) | 64 | |
| 17 | Keycaps set (Cherry-MX compatible)     | 1 | |

Optional LED. Choose either backlight or per-switch (not both)

| #  | Name                          | Quantity | Example URL                                           |
|----|-------------------------------|----------|-------------------------------------------------------|
| 17 | LED (backlight) WS2812B             | 12       | https://aliexpress.ru/item/32774508291.html |
| 18 | LED (per switch) SK6812 MINI-E      | 64       | https://aliexpress.ru/item/4000475685852.html |

Optional for I2C connection (instead of serial)

| #  | Name                          | Quantity | Example URL                                           |
|----|-------------------------------|----------|-------------------------------------------------------|
| 19 | Resistor 4.7K (through hole)  | 2        | https://aliexpress.ru/item/32882582185.html |

Optional

| #  | Name                          | Quantity | Example URL                                           |
|----|-------------------------------|----------|-------------------------------------------------------|
| 20 | OLED screen                   | 2        | https://aliexpress.ru/item/32798439084.html           |

## Build instructions

Are [here](https://github.com/vlkv/avalanche/blob/master/build_instructions.md). These instructions are very brief
and insufficient as a detaild build instructions for a beginner. That is why (if you are a beginner) I recommend you
to also read these resourses:
* [ErgoTravel Build Instructions](https://github.com/jpconstantineau/ErgoTravel/blob/master/BuildInstructions.md)
* [Jian Build Instructons](https://telegra.ph/Gajd-po-sborke-Jian-12-08)
* [Joric wiki](https://github.com/joric/jorne/wiki)


## Firmware

Is [here](https://github.com/vlkv/qmk_firmware/tree/master/keyboards/avalanche).
