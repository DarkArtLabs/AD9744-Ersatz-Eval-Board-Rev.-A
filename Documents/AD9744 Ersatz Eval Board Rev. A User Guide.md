# Assembly

The erstaz eval board is able to be soldered by hand. The footprints of many components have been extended to make the soldering process easier. It is reccomended to follow the general guidelines below when soldering components to the board.

  - Place and solder U1 (AD9744)
  - Place and solder all 0603 and 0805 size components (resistors, capacitors, LED)
  - Place and solder C14 (100uF)
  - Place and solder all through-hole components (pin headers, termianal block, test points, SMA connectors)
  - Attach standoffs or mounting hardware (optional)

# Interfaces

## J1

J1 is the digital input to the DAC. The CLK pin is the default clock input. The 3.3V pin supplies the digital section. 

## J2

J2 is an optional external clock input to the DAC. The port accepts a CMOS-level signal. JP2 must be closed to use this port.

## J3

J3 is the analog output of the DAC. It is impedance matched to 50 Ohms. 

# Setup

## JP1 - DAC Word Format

Header JP1 allows the selection of either 2's complement or unsigned binary DAC words to be written to the AD9744. Place a jumper on the right two pins to select unsigned binary and the left two pins to select 2's compelement. 

## JP2 - External Clock Enable

Solder jumper JP2 located on the rear of the board allows for the use of the external clock port J2. Close this jumper to enable the port.

Leaving this jumper open if supplying a clock through pin header J1. 

## JP3 - Analog and Digital Voltage Rail Selection

Placing a jumper on this header ties AVDD and DVDD together. This allows the user to power the ersatz eval board through the 3.3V pin on J1. Alternately, the 3.3V pin may be disconnected and the board powed through the terminal block. 

Removing the jumper on JP3 allows for the digital section to be powered through the 3.3V pin on header J1 and the analog section to be powered through the terminal block. 
