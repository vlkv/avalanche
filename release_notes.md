## Release notes


### v4
* Compacted and redesigned stuff around ProMicro.
* Column stagger was made less agressive.
* Less angle for the "pinky stagger" of the 5th and 6th colums.
* Changed OLED to horizontal one (SSD1306 128x64).
* Removed support for the background lighting (so, there is only per-switch lighting on board).
* Since v4.1: Changed the edge cuts of the PCB a little bit, so after breaking the numbers row the PCB is
  more neat and pretty. ATTENTION: this required changing the position of the three top mounting holes, so
  the top/bottom plates of **v4.0 and v4.1 are not compatible**.

### v3

* Changed the thumb cluster (see the image).
* Since v3.1: Fixed issue with per-switch LEDs facing down. Now, they facing up.


### v2.1

* Fixed issue with R1 resistor.


### v2.0

* Moved (a bit) thumb cluster to the center making the fourth thumb button more comfortable.
* Added the fifth button to the thumb cluster (mostly for rotary encoders).
* Added rotary encoders support.
* Rotated (a bit) three outer columns for better pinky reach.
* Changed the shape of top and bottom plates (as well as the PCBs).
* Added support for per-switch RGB lighting.
* Changed footprints for backlight RGB lighting.
* Changed footprints for switch sockets to a different ones.
* Moved reset button.
* Moved mounting holes.
* Other minor fixes...

Issues:
* Resistor R1 is turned upside down, making it harder to enable I2C.


### v1.1

The issue with TRRS socket has been fixed. So this version should be OK to build.


### v1.0

This is the very first prototype version. It had major issue: TRRS socket had a wrong position. It is not fatal,
you can fix it with some cutting with a file. It is not recommend to build this version.
