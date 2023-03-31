Keithley 615 Electrometer Printer Board Recreation
==================================================

This repo contains modern reproductions of the buffer/printer PCBs (PC209, PC218)
for the Keithley 615 electrometer.

Boards
------

 - PC218
   - Signal inverter/buffer board
   - Recreation of the origional PC218 schematic using modern SMD components is
     in the `PC218` directory
   - A simplified version using more modern ICs can be found in the `PC218v2` directory
 - PC209
   - Signal inverter/buffer and trigger board
   - Simplified version of the origional board can be found in the `PC209` directory
     - Same inverter/buffer scheme as PC218v2, with the origional trigger pulse
       generator and logic reduced down to discrete transistors, to simplify design.
 - Digital Interface Board
   - This will be a new board designed to connect to the 615 via the 50-pin
     Centronics connector
   - Planned features:
     - Passive data collection
     - Active triggering
     - USB-serial
     - RS-232 via DE-9
     - Ethernet

Photos
------

PC218 v2.2:
![Front of PC218 board v2.2](img/PC218_Rev2.2_Front.jpg)
![Rear of PC218 board v2.2](img/PC218_Rev2.2_Rear.jpg)

PC209 v1.0:
![Front of PC209 board v1.0](img/PC209_Rev1.0_Front.jpg)
![Rear of PC209 board v1.0](img/PC209_Rev1.0_Rear.jpg)

Interface/network board v1.0:
![Interface board v1.0](img/InterfaceBoard_Rev1.0.jpg)

50-pin test board v1.0:
![50-pin test board v1.0](img/TestBoard_Rev1.0.jpg)

