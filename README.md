# AD9744 Ersatz Eval Board Rev. A
This project contains a low cost evaluation board for the Analog Devices [AD9744](https://www.analog.com/media/en/technical-documentation/data-sheets/AD9744.pdf) 14-bit DAC.

![Layout](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/blob/main/Pictures/Layout.png)

  The ersatz evaluation board is a low-cost alternative to the evaluation board produced by Analog Devices which retails for approximately $500. The full BOM cost for this board including components, the board itself, tax, and shipping is about $100. 
The area of the PCB is 23 cm<sup>2</sup> and it is designed to be built on standard 2-layer FR4 by any low-cost PCB fabricator. All components sit on the top of the board and the design is nominally hand-solderable. 

# Features
  - Power board through pin header, or separately power analog section through terminal block
  - 2's complement or unisigned binary DAC word selectable using jumper
  - External clock input
  - 50 Ohm output impedance
  - Mounting holes for M2 hardware or standoffs
  - Test points on DAC output before balun

# Changes From Rev. -
The following changes from Rev. - have been implemented.
  - The position of D0 on header J2 has moved
  - DVDD now supplied by controlling device through 3.3V pin on header J2
  - Pin header & jumper included to power AVDD from DVDD
  - Board size increased to 48mm by 48mm
  - Trace from balun TR1 to Vout port J4 has been widened to approx. 55 Ohms
  - Position of external clock port J3 changed and terminating resistor R1 moved closer to J3
  - Updated BOM to include blue terminal block option for use with blue PCB
  - Minor changes to trace routing
  - Minor changes to skilscreen
