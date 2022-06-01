### This is a breakout shield for the Arduino Uno.

The V1 bare boards are available for $5 while they last: https://overkillsolar.com/product/spider-shield-v1/ If this is popular we will make some V1.1 boards for sale.

This project is open-source under the usual MIT or GPL3 license. You may use it for any purpose.
 
Every I/O pin is broken out into a .200" and .100" footprint which works with any shape of pluggable (or normal) screw connectors, or pin headers.

The intention was to allow a bunch of limit switches and sensors to plug in while keeping a low profile. Straight connections can also be used instead of right angle connectors. The shield can be used as shown or mounted upside down with the Arduino on top. Other Uno shaped shields (like the relay shield) can also stack with it, there is no interference with the connectors.

There are a bunch of extra points to connect 5v and ground in the middle as well as another full set of I/O pins. There is a jumper that connects all the 5v pins to the Arduino, or you can remove the jumper and back feed the shield from another 5v supply.


V1 boards turned out pretty good.    
V1.1 includes some minor fixes but I haven't had any boards made yet.    

### Changes on V1.1:    
- corrected one of the GND/5V silkscreen labels
- label the scl/sda pins on the Uno footprint
- closed the gap between the D3,D2 and A0,D13 connectors
- added a pin header for reset next to the button footprint
- connected the other 2 uno ground pins to the ground net
- added the Uno outline to the silkscreen
- enlarged the mounting holes to 3.2mm

## V1 Photos:    
![Just the board](https://github.com/FurTrader/uno-SPIDER-SHIELD-/blob/main/Photos_V1/IMG_7065.JPG)

![Partially assembled](https://github.com/FurTrader/uno-SPIDER-SHIELD-/blob/main/Photos_V1/IMG_7060.JPG)
