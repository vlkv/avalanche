## The Avalanche keyboard build instuctions


### Diodes

Both SMD and through-hole types of diodes are supported. I recommend through-hole ones, because (after you solder them)
you can use their wires as a pins for ProMicros.


### Switch sockets

I recommend the following way of soldering the switch sockets. Take the top plate, insert all switches into the top plate holes. Then place the top plate onto the PCB. Take switch sockets and place them to their dedicated places on the bottom side of the PCB. The switch sockets will be fixed with the switch pins stopping them from falling away or move anywhere around. Now solder the switch sockets to the PCB (with comfort).


### ProMicro sockets

Solder the sockets to the PCBs. Solder one pin, check that the row of sockets is positioned with a straight 90 degrees angle to the PCB. Resolder if it is not. Only after that solder other pins. When soldering the socket's pins keep your soldering iron away from the unused pads. You should not short circuit unused pads with the pins.

Solder the pins (remember the pieces of wire left from the diodes?) to the ProMicros. Put some painter's tape (or similar) between sockets and ProMicros before soldering the pins. Otherwise the pins could be soldered with the sockets.


### Reset switch and TRRS socket

Just solder them. It is simple.


### Choose Serial or I2C
I recommend to use I2C, because it provides less latency in communication between the halves of the
keyboard. And this latency difference is noticable (subjectively).

* For I2C you should solder resistors R1, R2 on the master (left by default) half.
  Then connect P1 with R1 (closest hole) and P2 with R2 (again the closest hole).
  Modify your qmk firmware to support I2C.
  Use only TRRS cable to connect keyboard halves.

* For Serial you should short circuit the W1 jumper. Modify your qmk firmware to support Serial.
  Use TRS or TRRS cable to connect keyboard halves.

This doc of the [QMK site](https://beta.docs.qmk.fm/using-qmk/hardware-features/feature_split_keyboard) has
additional information.


### Break off the numbers row

* Break off the numbers row, if you do not need/like it.
* If you are using per-switch LEDs, then short circuit the J9, J10, J11 jumpers.


### Choose per-switch or backlight LEDs
It is not recommended to install both per-switch and backlight LEDs (for aestetical reasons).

* For backlight LEDs, just solder them

* For per-switch LEDs, you should short circuit the data-in of the first backlight LED with the data-in of the first per-key LED with some wire (or data-in to data-out pins on all backlight LEDs). Of course, it is supposed that you do not install the backlight LEDs at all.


### Rotary encoders
* IMPORTANT NOTE: Only 1 rotary encoder could be installed on each half.
* Solder all 7 pins of rotary encoders to the PCB this fixes the encoder the best.
* Do not install both kailh socket and rotary encoder into the same switch slot on the PCB. Install either one.
