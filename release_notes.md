## Release notes

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
* New footprints for the switch sockets have somewhat loose holes. Need to change the footprints.

### v1.1

The issue with TRRS socket has been fixed. So this version should be OK to build.


### v1.0

This is the very first prototype version. It had major issue: TRRS socket had a wrong position. It is not fatal,
you can fix it with some cutting with a file. It is not recommend to build this version.
