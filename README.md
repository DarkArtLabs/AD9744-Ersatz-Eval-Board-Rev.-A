# AD9744 Ersatz Eval Board
This is a low-cost evaluation board for the Analog Devices [AD9744](https://www.analog.com/en/products/ad9744.html) 14-bit DAC.

![3D Render Front](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/blob/main/Pictures/AD9744%20Ersatz%20Eval%20Board%20Rev.%20A%20RT%20Render%202.png)

![3D Render 2](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/blob/main/Pictures/AD9744%20Ersatz%20Eval%20Board%20Rev.%20A%20RT%20Render.png)

The ersatz evaluation board is a low-cost alternative to the AD9744-FMC-EBZ evaluation board produced by Analog Devices which retails for approximately $500. The full BOM cost for this project including components, the board itself, tax, and shipping is about $100. 
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
A set of downloads is included below for those who simply wish to make their own ersatz eval board. Included is a PDF schematic, BOM, gerbers, and user guide.

The KiCAD design files for this project are included here and may used by those who wish to modify the design of the ersatz eval board. 

# Downloads 

## Schematic
A ![PDF of the schematic](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/blob/main/Documents/AD9744%20Ersatz%20Eval%20Board%20Rev.%20A%20Schematic.pdf) is included in Documents. It defines all electrical connections, component values, and component tolerances. DNP signifies that no part is to be placed.

## Bill of Materials (BOM)
A ![BOM](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/blob/main/Documents/AD9744%20Ersatz%20Eval%20Board%20Rev.%20A%20BOM.csv) is included in Documents. It contains manufacturer part numbers and quantities for every component. It also contains Mouser part numbers for easy cross reference. The BOM may be uploaded to the Mouser website and a shopping cart with correct quantities will automatically be generated. Parts may be substituted as long as they meet the minimum tolerances and footprint dimensions. 

To match blue and green PCBs, the BOM contains options for green and blue terminal blocks.

## Gerbers, Drill File, Drill Map
A set gerbers, a drill file, and a drill map are included in the Gerbers directory. The files have been generated according to the specifications that JLCPCB requires, but they will likely work at other fabricators such as PCBWay or OSHPARK.

[AD9744 Ersatz Eval Board Rev. A Gerbers.zip](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/blob/ef1a7e2815231d8058b779c77f9b8090e2d1c047/Gerbers/AD9744%20Ersatz%20Eval%20Board%20Rev.%20A%20Gerbers.zip)

## User Guide
The ![AD9744 Ersatz Eval Board Rev. A User Guide](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/blob/main/Documents/AD9744%20Ersatz%20Eval%20Board%20Rev.%20A%20User%20Guide.md) contains information on board assembly, setting options with jumpers, and a detailed description of the board. 

# Performance (TBD)
  - Power consumption
  - VSWR
  - Pout
  - Fmax
  - Output spectrum
