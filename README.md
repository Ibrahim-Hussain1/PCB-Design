# PCB-Design of a DC Power Meter

This project follows a full development cycle for designing a low cost, portable, PIC18 based DC
power meter and a full set of firmware and production files. For measurement the
power meter will interface with the device under test (DUT) via wires.
The power meter has the following characteristics:
1. Measure voltage between 0-10 V (DC).
2. Measure current between 0-1 A (DC).
3. Calculate power/energy.
4. Display the measured values.
The desired specification for the device is listed below:
1. Voltage measurement:
   Measure voltage applied to the device under test (DUT)
   As above, with two decimal points precision (in volts e.g. 4.73V)
2. Current Measurement:
   Measure current through the device under test (DUT)
   As above, with two decimal points precision (in amps e.g. 0.45 A)
3. Power Measurement:
   Measure instantaneous power in mW unit
   Measure energy in mWh unit

To finalize the project, the design was implemented on a custom PCB. 

Schematic on Proteus :
![Screenshot (140)](https://github.com/Ibrahim-Hussain1/PCB-Design/assets/161763368/bf361d8f-928e-4771-a3d6-a024b920ff1a)

PCB Design: 
<img width="283" alt="pcb1" src="https://github.com/Ibrahim-Hussain1/PCB-Design/assets/161763368/5369c9d2-42a8-4f34-aa7c-ec8f62ccf82e"> <img width="268" alt="pcb1 (1)" src="https://github.com/Ibrahim-Hussain1/PCB-Design/assets/161763368/eef1c08a-a06b-44c9-b78c-09f0e5fdf2db"> <img width="366" alt="pcb" src="https://github.com/Ibrahim-Hussain1/PCB-Design/assets/161763368/07e6a156-f996-4686-874a-13bbd42d6be9">



