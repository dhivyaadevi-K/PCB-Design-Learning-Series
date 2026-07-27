\# 05 - Thermistor-Based Temperature Indicator Circuit



A beginner-friendly PCB project designed in KiCad 9 to practice building a temperature-sensing circuit using a thermistor in a voltage divider, driving an LED through a transistor switch.



Part of my \*\*PCB Design Learning Series\*\*, where I design and document circuits from basic to advanced using KiCad.



\## Tools



Designed in \*\*KiCad 9\*\*



\## Overview



R1 (10k) and TH1 (thermistor) form a voltage divider. As temperature changes, the thermistor's resistance changes, shifting the voltage at the divider's midpoint feeding Q1's base. This turns Q1 on or off, switching the LED (D1) accordingly.



| J1 Pin | Signal | Description        |

|--------|--------|---------------------|

| 1      | GND    | Common ground        |

| 2      | +5V    | Power input          |



\## How It Works



\- Thermistors are temperature-dependent resistors — most common types (NTC) decrease in resistance as temperature rises

\- As temperature changes, the divider midpoint voltage shifts, turning Q1 on or off

\- R3 (330 Ω) limits current through the LED

\- This circuit demonstrates the same voltage-divider + transistor-switch principle as the LDR project, but using a thermistor instead — useful for basic over-temperature indicators



\## Features



\- Through-hole PCB, beginner-friendly assembly

\- Thermistor-based voltage divider for temperature sensing

\- NPN transistor (BC547) as a switch

\- Visual LED indicator triggered by temperature change

\- ERC and DRC verified

\- Gerber and drill files included, ready for fabrication



\## Components



| Component             | Qty |

|-------------------------|-----|

| Thermistor (TH1)         | 1   |

| NPN Transistor (Q1)      | 1   |

| LED (D1)                 | 1   |

| 330 Ω Resistor (R3)      | 1   |

| 10k Resistor (R1)        | 1   |

| 2-Pin Socket (J1)        | 1   |



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

