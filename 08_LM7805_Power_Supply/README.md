\# 08 - LM7805 5V Voltage Regulator Board



A beginner-friendly PCB project designed in KiCad 9 to practice building a linear voltage regulator circuit using the LM7805, a common fixed 5V regulator IC.



Part of my \*\*PCB Design Learning Series\*\*, where I design and document circuits from basic to advanced using KiCad.



\## Overview



U1 (LM7805, TO-220 package) takes an unregulated DC input voltage (VR\_IN) and outputs a stable, regulated 5V (VR\_OUT). C1 and C2 are input/output filter capacitors that stabilize the regulator and suppress noise/oscillation.



| J1 Pin | Signal  | Description                     |

|--------|---------|-----------------------------------|

| 1      | VR\_IN   | Unregulated DC input (typically 7–25V for LM7805) |

| 2      | GND     | Common ground                     |



| J2 Pin | Signal   | Description             |

|--------|----------|---------------------------|

| 1      | VR\_OUT   | Regulated 5V output       |

| 2      | GND      | Common ground              |



\## How It Works



\- Unregulated DC voltage enters at VI (pin 1) of U1

\- The LM7805 internally regulates this down to a fixed, stable 5V output at VO (pin 3)

\- C1 (0.33 µF) on the input side filters ripple/noise from the input source

\- C2 (0.1 µF) on the output side stabilizes the regulator and filters high-frequency noise on the output

\- GND (pin 2) is the common reference for both input and output



\## Features



\- Through-hole PCB, beginner-friendly assembly

\- Fixed 5V linear voltage regulation using LM7805

\- Input and output filter capacitors for stable operation

\- ERC and DRC verified

\- Gerber and drill files included, ready for fabrication



\## Components



| Component                  | Qty |

|------------------------------|-----|

| LM7805 Voltage Regulator (U1) | 1  |

| 0.33 µF Capacitor (C1)        | 1  |

| 0.1 µF Capacitor (C2)         | 1  |

| 2-Pin Header (J1)             | 1  |

| 2-Pin Header (J2)             | 1  |



\## Repository Contents



\- KiCad Schematic

\- KiCad PCB

\- Gerber Files

\- Drill Files

\- ERC Report

\- DRC Report

\- Images



\## Images



\### Schematic

!\[Schematic](Images/Schematic.png)



\### PCB Layout

!\[PCB Layout](Images/PCB\_Layout.png)



\### 3D View

!\[3D View - Front](Images/3D\_Front.png)

!\[3D View - Back](Images/3D\_Back.png)



\## Tools



Designed in \*\*KiCad 9\*\*.

