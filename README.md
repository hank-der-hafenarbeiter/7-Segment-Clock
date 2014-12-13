7-Segment-Clock
===============

Schematic/PCB-Board for building a 4 digit seven segment display wall clock.


Both files were created using EAGLE 6.5.0


IMPORTANT:
I'm using the IRFML 8244 n-channel SOT-23. As of yet this is not changed in the schematics!


Greater picture:

This is a schematic/board i'll use to drive a ~80cm x ~50cm 7-segment digit on my wall. The display will use 12V RGB led strips with a power of ~7,2W/m. The board will make it possible to drive the 12V@180mA one segmetn needs from an ordinary arduino pin.

The "SEG#" pins will be connected to the kathode side of the strip while the anode side will be connected to the RGB led driver. The "PIN#" pins will be connected to the digital pins of an Arduino Mega. I will use the PWM pins to connect to the LED driver.

In the end i'll use 4 of these boards two drive for digits to make a wall clock.

