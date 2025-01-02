# Assembly & User Guide

This guide is broken into two parts, the first is a guide on assembling and soldering the board together. The second part describes how to use the AD9744 ersatz eval board.

## Assembly Guide

> [!IMPORTANT]
> Hand assembly of this board is not recommended for those new to SMD soldering. This guide assumes the user knows how to solder and has the proper equipment to proceed.

The general assembly process will be to install the DAC, next the small passives and LED, then the large SMD parts, and finally the through-hole parts.

  1. Solder in U1 (AD9744), verify pin 1 is up and to the left

  2. Solder in R5 (2k, 1%), R4 (10k), and C1 (0.1u)

  3. Solder in R2 (50) and R6 (50)

  4. Solder in C9, C11, C12, and C13 (all 0.1u)

  5. Solder in C7 and C10 (10u, 16V)

  6. Solder in C6 and C8 (10u, 25V)

  7. Solder in R1 (50)

  >[!TIP]
  > Soldering R1 directly to the center and ground pins of J2 on the back of the board will provide a better termination.

  8. Solder in D1 (LED) with the cathode pointing up toward the terminal block

  9. Solder in R8 (13) and C4 (0.1u)

  10. Solder in FB2, C5 (0.1u), and FB1

  11. Solder in C14 (100u) and TR1

  >[!TIP]
  > TR1 is upside down with respect to the orientation of the other parts. Pin 1 is toward the bottom right corner of the board.
  > Trim the legs of TR1 to fit the pads before soldering.

  12. Solder in TP1, TP2, TP3, and TP4

  13. Solder in J1 (2x9 pin header), JP1 (3 pin), J4 (terminal block), and JP3 (2 pin)

  14. Solder in J2 and J3 (SMA connectors)

  15. Install M2 size stand-offs in the corner mounting holes (Optional)

## User Guide

