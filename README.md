# AD9744 Ersatz Eval Board
A low-cost evaluation board for the Analog Devices [AD9744](https://www.analog.com/en/products/ad9744.html) 14-bit DAC.

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
Downloads are available below for those who wish to make their own ersatz eval board. The KiCAD project files are also available for those who wish to modify the design. 

## Schematic
The schematic may also be viewed above in the Documents directory.

## Bill of Materials
The BOM may also be viewed above in the Documents directory. It contains manufacturer part numbers and quantities for every component. It also contains Mouser part numbers for easy cross reference. The BOM may be uploaded to the Mouser website and a shopping cart with correct quantities will automatically be generated. Parts may be substituted as long as they meet the minimum tolerances and footprint dimensions. 

To match blue and green PCBs, the BOM contains options for green and blue terminal blocks on lines 7a and 7b, respectively. Only one terminal block is needed for this project. 

To open this file with Excel, it is recommended to import the CSV data. Simply opening the file with Excel will cause formatting errors. 

## Gerbers, Drill File, Drill Map
These files have been generated according to the specifications that JLCPCB requires, but they will likely work at other fabricators such as PCBWay or OSHPARK.

## User Guide
The user guide may also be viewed above in the Documents directory. It contains information on assembly, I/O ports, and jumper options.

# Performance

## Power Consumption

For AVDD and DVDD rails tied together. Device active and generating waveform at 210 MSPS.

$`V_{in} = 3.295 \; [V]`$

$`I_{in} = 65 \; [mA]`$

$`P_{cons} = 214.2 \; [mW]`$

## VSWR

Vout S11 Smith Chart: 10 MHz - 100 MHz 
![S11 Smith No Markers](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/blob/main/Pictures/AD9744_ErsatzEval_RevA_SN1_Rdiff%3D100_Vout_2to1Balun_62Ohms_SmithNoMarkers_9JAN25.png)

Vout S11 Smith Chart: 10 MHz - 100 MHz (markers every 10 MHz)
![S11 Smith Markers](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/blob/main/Pictures/AD9744_ErsatzEval_RevA_SN1_Rdiff%3D100_Vout_2to1Balun_62Ohms_SmithMarkers_9JAN25.png)

Vout S11 Log Magnitude: 10 MHz - 100 MHz (markers every 10 MHz)
![S11 Log Magnitude Markers](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/blob/main/Pictures/AD9744_ErsatzEval_RevA_SN1_Rdiff%3D100_Vout_2to1Balun_62Ohms_LogMag_9JAN25a.png)
  
## Output Power

0 dBm Single Tone: 26.25 MHz (210 MSPS)
![Single 26.25 MHz tone](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/blob/main/Pictures/AD9744%20Ersatz%20Eval%20Board%20Rev.%20A%2026.25MHz%20tone.png)

# Downloads

Schematic: ![AD9744 Ersatz Eval Board Rev. A Schematic.pdf](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/releases/download/A0/AD9744.Ersatz.Eval.Board.Rev.A.Schematic.pdf)

Gerbers: ![AD9744 Ersatz Eval Board Rev. A Gerbers.zip](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/releases/download/A0/AD9744.Ersatz.Eval.Board.Rev.A.Gerbers.zip)

BOM: ![AD9744 Ersatz Eval Board Rev. A BOM.csv](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/releases/download/A0/AD9744.Ersatz.Eval.Board.Rev.A.BOM.csv)

User Guide: ![AD9744 Ersatz Eval Board Rev. A User Guide.pdf](https://github.com/DarkArtLabs/AD9744-Ersatz-Eval-Board-Rev.-A/releases/download/A0/AD9744.Ersatz.Eval.Board.Rev.A.User.Guide.pdf)

