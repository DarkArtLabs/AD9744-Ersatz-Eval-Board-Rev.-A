# Assembly

The ersatz eval board is able to be soldered by hand. The footprints of many components have been extended to make the soldering process easier. It is recommended to follow the general guidelines below when soldering components to the board.

  - Place and solder U1 (AD9744)
    - Orient pin 1 up and to the left (toward the terminal block)
    
  - Place and solder all 0603 and 0805 size components (resistors, capacitors, LED)
    - Point LED cathode up toward terminal block
    
  - Place and solder C14 (100uF electrolytic)
    - Positive terminal oriented downwards toward U1
    
  - Place and solder TR1 (T1-6T+)
    - Orient pin 1 down and to the right (toward TP3)
    
  - Place and solder all through-hole components (pin headers, terminal block, test points, SMA connectors)
  
  - Attach M2 size standoffs or mounting hardware (optional, recommended)

# Interfaces

## J1 - 2x9 Digital Input

Digital input to the DAC. The CLK pin is the default clock input. The 3.3V pin supplies the digital section. 

## J2 - External Clock Input

Optional external clock input to the DAC. The port accepts a CMOS-level signal. JP2 must be closed to use this port.

## J3 - Analog Voltage Output

Analog output of the DAC. It is impedance matched to 50 Ohms. 

## J4 - Terminal Block

The 3.3V input to the analog section.

# Jumpers

## JP1 - DAC Word Format

Allows the selection of either 2's complement or unsigned binary DAC words to be written to the AD9744. Place a jumper on the right two pins to select unsigned binary and the left two pins to select 2's complement. 

## JP2 - External Clock Enable

Allows for the use of the external clock port J2. Close this jumper to enable the port. Located on rear of the board.

Leaving this jumper open if supplying a clock through pin header J1. 

## JP3 - Analog and Digital Voltage Rail Selection

Placing a jumper on this header ties AVDD and DVDD together. This allows the user to power the ersatz eval board through the 3.3V pin on J1. Alternately, the 3.3V pin may be disconnected and the board powered through the terminal block. 

Removing the jumper on JP3 allows for the digital section to be powered through the 3.3V pin on header J1 and the analog section to be powered through the terminal block. 

# Test Points

## TP1 - Iout+

Test point is on DAC differential output IoutA (non-inverting output) immediately before the balun. This allows for DC voltages and slow signals (f<15kHz) to be measured as they will not pass through the balun. This test point should measure full scale output for a full-scale DAC word (0x3FFF). 

## TP2 - Iout-

Test point is on DAC differential output IoutB (inverting output) immediately before the balun. This allows for DC voltages and slow signals (f<15kHz) to be measured as they will not pass through the balun. This test point should measure full scale output for a min-scale DAC word (0x0000). 

## TP3 - Ground

Test point is connected to ground.

## TP4 - CLK

Test point measures the clock input from either header J1 or port J2. 


