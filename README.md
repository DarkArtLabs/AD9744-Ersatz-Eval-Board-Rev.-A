# AD9744 Ersatz Eval Board
This project is a low-cost evaluation board for the Analog Devices [AD9744](https://www.analog.com/media/en/technical-documentation/data-sheets/AD9744.pdf) 14-bit DAC.

![Layout](/Pictures/AD9744 Ersatz Eval Board Rev. A Front.png)

The ersatz evaluation board is a low-cost alternative to the evaluation board produced by Analog Devices which retails for approximately $500. The full BOM cost for this project including components, the board itself, tax, and shipping is about $100. 
The area of the PCB is 23 cm<sup>2</sup> and it is designed to be built on standard 2-layer FR4 by any PCB fabricator. All components sit on the top of the board and the design is hand-solderable. 

# Features
  - Power the board through pin header, terminal block, or separately power analog and digital sections
  - Select 2's complement or unsigned binary DAC word using a jumper
  - External clock input
  - 50 Ohm output impedance
  - Test points on DAC output before balun
  - Mounting holes for M2 hardware or standoffs
  - BOM options for blue and green components to match blue or green soldermask

# What is Included
This project includes everything needed to make the ersatz evaluation board. 

## Schematic
A ![PDF of the schematic](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/blob/main/Documents/AD9744%20Ersatz%20Eval%20Board%20Rev.%20A%20Schematic.pdf) is included in Documents. It defines all electrical connections, component values, and component tolerances. DNP signifies that no part is to be placed.

## Bill of Materials (BOM)
A ![BOM](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/blob/main/Documents/AD9744%20Ersatz%20Eval%20Board%20Rev.%20A%20BOM.csv) is included in Documents. It contains manufacturer part numbers and quantities for every component. It also contains Mouser part numbers for easy cross reference. The BOM may be uploaded to the Mouser website and a shopping cart with correct quantities will automatically be generated. Parts may be substituted as long as they meet the minimum tolerances and footprint dimensions. 

To match blue and green PCBs, the BOM contains options for green and blue terminal blocks.

## Gerbers, Drill File, Drill Map
A set gerbers, a drill file, and a drill map are included in the Gerbers directory. The files have been generated according to the specifications that JLCPCB requires, but they will likely work at other fabricators such as PCBWay or OSHPARK. These files may be compressed into a ZIP file and uploaded to the PCB fabricator of your choice.

## User Guide
The ![AD9744 Ersatz Eval Board Rev. A User Guide](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/blob/main/Documents/AD9744%20Ersatz%20Eval%20Board%20Rev.%20A%20User%20Guide.md) contains information on board assembly, setting options with jumpers, and a detailed description of the board. 

# Performance (TBD)
  - Power consumption
  - VSWR
  - Pout
  - Fmax
  - Output spectrum
