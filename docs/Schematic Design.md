---
title: Schematic Desgin
---
Below is the Humidity and Temperature subsystem created for Team 308, Fresh Start. 
The system uses the PIC microcontroller and regulates the 9V using an LDO and a switch to start the device up.
It is the individual susbsystem, but in the future will need to use the same power source to charge other teamates systems.
The PCB will be made to be compact with surface mount applications being the focus of this design. I also had to ensure that the surface mount chips were not too small to be used in the design due to the needs to place them down onto the actual pcb.

Download PDF: [Schematic_Design_308Ethan.pdf](https://github.com/user-attachments/files/19037395/Schematic_Design_308Ethan.pdf)
[Uploading Schematic_Design_308Ethan.PrjPcb…]()

Download Project: [Project.zip](https://github.com/user-attachments/files/19037401/Project.zip)


| Component- Componet Name                | Voltage Range (V) | Typical Voltage (V) | Max Current (mA) | Power (mW) |
|--------------------------|-------------------|---------------------|------------------|------------|
| Microcontroller - PIC18F47Q10      | 2.3V-5.5V       | 3.3V                | 250mA            | 825mW      |
| Blue surface mount LED - 597-6602-107F  |    2.8V - 3.6V               |       3.3V              |        125mA          |    108mW        |
| Switch - B3U-1000P | 0-24 VDC | 0-24 V DC | 50 mA | 165mW|
| Humidity Sensor - HDC1010YPAR              | 2.7V - 5.5V       | 3.3V                | 20mA             | 66mW       |
| **Total (maximum) Power Consumption** | -                 | 3.3V                | 240mA            | 1164mW      |

All these components use the 3.3V power rail, with currents listed above

External Power Source

| Component- Componet Name                | Supply Voltage | Output voltage | Max Current (mA) | Total current (mW) |
|--------------------------|-------------------|---------------------|------------------|------------|
| 9V power - #0930 Peralta labs     | Wall 120V      | 9V               | 5000            | 50000      |
|   |                  |                    |                 |          |
|  |  |  |  | |
| 3.3V regulator AMS1117-3.3V              | 9V       | 3.3V                | 2000            | 2000       |

The power budget has helped to estimate power needs by allowing us to use the correct fuses and to use the appropriate LDO to regulate voltage

![Screenshot 2025-02-28 194323](https://github.com/user-attachments/assets/f0e1eccb-152e-43f5-8203-a0a542bfda6f)

