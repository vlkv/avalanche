# Avalanche keyboard

Avalanche keyboard is an ergonomic split keyboard with 4x6 (or 3x6 if you break off the 'digits' row) column staggered keys, 
5 thumb keys, 1 key for pinky (break off-able too) and 1 additional key for index finger (62 keys total). QMK firmware for Avalanche is [here](https://github.com/vlkv/qmk_firmware/tree/master/keyboards/avalanche).

Avalanche design was inspired by
* [Corne](https://github.com/foostan/crkbd) - for arc-shaped thumb cluster.
* [Jorne](https://github.com/joric/jorne), [Jiran](https://github.com/Ladniy/jiran), [Jian](https://github.com/KGOH/Jian-Info) - for additional key for the pinky.
* [Lily58](https://github.com/kata0510/Lily58) - for additional key for the index finger.
* [Kyria](https://github.com/splitkb/kyria) - for additional key for the thumb.

## Parts list

| #  | Name                          | Quantity | Example URL                                           |
|----|-------------------------------|----------|-------------------------------------------------------|
| 1  | PCB                           | 2        | |
| 2  | Top plate                     | 2        | |
| 3  | Bottom plate                  | 2        | |
| 4  | ProMicro (ATmega32U4 5V/16MHz)| 2        | https://aliexpress.ru/item/2010847161.html            |
| 5  | Sockets for ProMicro 3.5mm    | 2        | https://aliexpress.ru/item/32899635835.html or https://www.chipdip.ru/product0/8004277524 or https://www.chipdip.ru/product/110-87-424-41-001101           |
| 6  | Kailh hotswap sockets         | 62       | https://aliexpress.ru/item/32903471019.html           |
| 7  | Diode 1N4148 (SMD or through hole)  | 62       | https://www.chipdip.ru/catalog/diodes-pulse?gq=1N4148 |
| 8  | Resistor 4.7K (through hole)        | 2        | https://www.chipdip.ru/product0/1849 |
| 9  | TRRS sockets PJ320A                 | 2        | https://aliexpress.ru/item/32368285821.html or http://www.dart.moscow/index.php?productcode=40634 | 
| 10 | TRRS Cable (straight connectors)    | 1        |  |
| 11 | Reset button (DIP switch)           | 2        | https://aliexpress.ru/item/4000209910403.html |
| 12 | Bumpons for bottom plate (set)      | 1        | https://aliexpress.ru/item/32912066603.html or https://aliexpress.ru/item/32680543746.html |
| 13 | OLED screen                         | 2        | https://aliexpress.ru/item/32798439084.html |
| 14 | LED SK6812 3535 BL 3.5mm            | 18       | https://aliexpress.ru/item/32623583544.html |
| 15 | M2 screws                           | 18       | https://aliexpress.ru/item/32976056190.html |
| 16 | M2 standoffs 3mm (or 4mm?)          | 18       | https://aliexpress.ru/item/32597776358.html |
| 17 | Keyboard switch (Cherry-MX compatible) | 62 | | 
| 18 | Keycaps set (Cherry-MX compatible)     | 1 | |

## Build instructions
Avalanche does not have own bulid instructions yet. But there are a lot of relevant information in:
* [Joric wiki](https://github.com/joric/jorne/wiki)
* [ErgoTravel Build Instructions](https://github.com/jpconstantineau/ErgoTravel/blob/master/BuildInstructions.md)
* [Jian Build Instructons](https://telegra.ph/Gajd-po-sborke-Jian-12-08)

## Images

![Avalanche PCBs 3D view](/images/avalanche62_PCBs_3d_model.png)
![Avalanche PCBs 3D view](/images/avalanche50_PCBs_3d_model.png)
![Avalanche PCBs 3D view](/images/avalanche48_PCBs_3d_model.png)

![Avalanche PCBs model](/images/avalanche_mockup_03.png)

![Avalanche mockup](/images/avalanche_mockup_02.jpg)
