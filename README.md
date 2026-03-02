# Transistor-Based-Time-Delay-Relay-with-Latching-Control
Transistor-Based Time-Delay Relay with Latching Control

Transistor-Based Time-Delay Relay with Latching Control

This project is a 9V transistor-based timer and relay control circuit that combines a time-delay function with a bistable (memory) action. It uses only discrete components (BJTs, resistors, capacitor, diode, and relay) — no ICs.

Main Features:
•	Adjustable time delay using capacitor C1 (100µF) and resistors.
•	Latching (memory) behavior using a transistor feedback network.
•	Relay output (RL1) to control external loads.
•	Status LEDs:
•	D1 (Red) → Indicates intermediate / timing state.
•	D2 (Green) → Indicates relay activated.
•	Flyback diode protection across the relay coil.

<img width="1090" height="736" alt="image" src="https://github.com/user-attachments/assets/b07c4fb0-290a-4792-89ae-2f87f802052a" />

How It Works:

•	Power Section (Left Side)
•	The 9V battery powers the circuit.
•	C1 (100µF) creates a charging delay when power is applied.
•	The RC network determines how long the delay lasts.
•	Control & Latch Section (Middle)
•	Transistors Q1 and Q3 form a control stage that processes the delayed signal.
•	The resistor network (R2, R3, R4, R5) creates a biasing and feedback system.
•	SW1 allows manual triggering/resetting.
•	Driver Stage (Right Side)
•	Q2 acts as a switching transistor.
•	When activated, it:
•	Turns ON the red LED (D1).
•	Drives Q4, which energizes the relay.
•	The relay then powers the green LED (D2) or an external load.
•	Protection
•	A diode across the relay coil prevents voltage spikes when switching OFF.
Applications
•	Delayed power-on relay
•	Auto shutoff timer
•	Soft-start control
•	Simple alarm or automation system

<img width="578" height="1027" alt="image" src="https://github.com/user-attachments/assets/c3cdf845-36d4-4383-8198-835d65914287" />

 
