ASSEMBLY AND WIRING

Given below are the steps to assemble this circuit:

FLEX SENSOR ASSEMBLY


1.
SOLDER

Solder jumper wires to the flex sensor to make connections to the breadboard easier.

2.
ATTACH THE FLEX SENSOR

Attach the other ends of the jumper wires to the breadboard



3. 
ATTACH THE RESISTOR

Since the Flex sensor is a variable resistor, it does not matter which side is connected to the resistor. In this project, I have connected the thick strip to the resistor.


DRV2605 MOTOR DRIVER ASSEMBLY


4.
PREPARE THE HEADER STRIP

Cut the header strip to the length required and insert it into the breadboard with the long pins down.


5.
PLACE THE BREAKOUT BOARD

Place the DRV 2605 over the header strip so that the short pins poke through the holes.


6.
SOLDER

Solder all the pins for more reliable contact. Be sure to solder the longer Power/Data pin first.


7.
ATTACH THE MOTOR

Attach the motor directly into the Motor+ and Motor- pads. To do this, slip the wires into the holes in the middle of the pads.


8.
SOLDER

Solder the wires in place.


WIRING

9.
	?	Connect the 5V to one end of the breadboard to create a common 5V source.
	?	Connect a GND pin next to the 5V to create a common GND.
	?	Connect the thin side of the flex sensor to GND.
	?	Connect the thick side (the one that is already connected to the resistor) to Analog pin A0.
	?	Connect the other end of the resistor to 5V.
	?	Connect Vin in the DRV2605 to 5V.
	?	Connect GND in the DRV2605 to the common GND.
	?	Connect the SCL pin to Analog pin A5.
	?	Connect the SDA pin to Analog pin A4.
10.
YOU?RE DONE!

Check that all the connections are secure before moving on.






