\# 02 - Transistor Buzzer Driver



A beginner-friendly PCB project designed in KiCad 9 to practice driving a higher-current load (buzzer) using a low-current logic/GPIO signal through an NPN transistor switch.



Part of my \*\*PCB Design Learning Series\*\*, where I design and document circuits from basic to advanced using KiCad.



\## Tools



Designed in \*\*KiCad 9\*\*



\## Overview



A simple buzzer driver circuit. The BUZZER\_IN signal (e.g. from a microcontroller GPIO) drives the base of an NPN transistor (Q1) through a 1k current-limiting resistor. When BUZZER\_IN goes high, Q1 switches on, completing the ground path for the buzzer (BZ1) and activating it.



This is a common \*\*low-side switching\*\* technique — used whenever a low-current control signal needs to drive a higher-current component like a buzzer, relay, or motor that the GPIO pin can't power directly.



| J1 Pin | Signal     | Description                          |

|--------|------------|----------------------------------------|

| 1      | +5V        | Power input for the buzzer            |

| 2      | BUZZER\_IN  | Control signal, drives Q1 base via R1 |

| 3      | GND        | Common ground                         |



\## How It Works



\- \*\*BUZZER\_IN high\*\* → current flows through R1 into Q1's base → Q1 turns on → completes buzzer's ground path → buzzer sounds

\- \*\*BUZZER\_IN low\*\* → Q1 stays off → buzzer circuit open → silent

\- R1 (1k) limits base current into Q1, protecting it from excess current

\- Q1 (MMBT2222A) acts as a switch, not an amplifier, in this configuration



\## Features



\- Through-hole PCB, beginner-friendly assembly

\- NPN transistor (MMBT2222A) as a low-side switch

\- Base current-limiting resistor (1k)

\- ERC and DRC verified

\- Gerber and drill files included, ready for fabrication



\## Components



| Component          | Qty |

|----------------------|-----|

| Buzzer (BZ1)          | 1   |

| NPN Transistor (Q1)   | 1   |

| 1k Resistor (R1)      | 1   |

| 3-Pin Header (J1)     | 1   |



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

