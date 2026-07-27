\# 06 - Potentiometer LED Dimmer



A beginner-friendly PCB project designed in KiCad 9 to practice manual brightness control of an LED using a potentiometer as a variable voltage divider.



Part of my \*\*PCB Design Learning Series\*\*, where I design and document circuits from basic to advanced using KiCad.



\## Tools



Designed in \*\*KiCad 9\*\*



\## Overview



R1 (220 Ω) and RV1 (potentiometer) form an adjustable voltage divider feeding the LED (D1). Turning the potentiometer's wiper changes the voltage delivered to the LED, allowing manual brightness adjustment from off to full brightness.



| J1 Pin | Signal | Description        |

|--------|--------|---------------------|

| 1      | +5V    | Power input          |

| 2      | GND    | Common ground        |



\## How It Works



\- +5V feeds through R1 into RV1 (potentiometer), which acts as a variable resistor

\- The potentiometer's wiper (terminal 2) taps off a variable voltage, which drives the LED

\- Turning the pot's wiper toward one end increases voltage to the LED (brighter); toward the other end decreases it (dimmer)

\- R1 (220 Ω) protects the LED from excess current even when the potentiometer is at its lowest resistance setting



\## Features



\- Through-hole PCB, beginner-friendly assembly

\- Manual LED brightness control via potentiometer

\- Current-limiting resistor to protect the LED at all pot settings

\- ERC and DRC verified

\- Gerber and drill files included, ready for fabrication



\## Components



| Component               | Qty |

|--------------------------|-----|

| Potentiometer (RV1)      | 1   |

| LED (D1)                 | 1   |

| 220 Ω Resistor (R1)      | 1   |

| 2-Pin Header (J1)        | 1   |



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

