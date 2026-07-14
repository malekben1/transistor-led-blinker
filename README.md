LED Flasher — Astable Multivibrator
 
A small PCB project featuring two alternating blinking LEDs, based on a classic
two-transistor astable multivibrator circuit (no microcontroller required).

📷 Overview
<img width="364" height="457" alt="image" src="https://github.com/user-attachments/assets/be06843d-4a53-4e59-9da8-a9641b658149" />
<img width="339" height="436" alt="image" src="https://github.com/user-attachments/assets/72986fb6-d219-44fd-9259-dc2d40561b6e" />

Operating Principle

The circuit is an **astable multivibrator**: two transistors (Q1 and Q2)
switch ON and OFF alternately, never reaching a stable state. This continuous
switching makes LEDs D1 and D2 blink one after the other, similar to a traffic
light alternating between two states.

Each capacitor (C1 and C2) charges gradually through a base resistor
(R3 and R4). Once the voltage reaches the transistor switching threshold,
it activates the opposite transistor, reversing the circuit state and restarting
the cycle.

🔌 Power Supply

- Input voltage: **+9V DC** through connector J1
- Common **GND** connection

📁 Repository Structure


├── p1.PrjPcb              # Altium Designer project file
├── Sheet1.SchDoc          # Electrical schematic
├── PCB1.PcbDoc            # PCB layout file
├── p1.PrjPcbStructure     # Project structure file


