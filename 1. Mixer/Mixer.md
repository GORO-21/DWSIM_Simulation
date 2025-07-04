Aim: To calculate the outlet stream’s temperature, pressure and molar composition for both pressure handling options that is minimum and average.

Data:
•	Inlet stream 1 (Methanol rich Stream) : 80 mol% methanol, 20 mol% water, Flowrate : 100kmol/h , T : 25 °C , P : 2 bar

•	Inlet stream 2 (Water rich Stream) : 10 mol% methanol, 90 mol% water, Flowrate : 50kmol/h, T : 40 °C , P : 1.5 bar 

DWSIM Block:

•	Mixer Specification

o	Unit operation – Mixer

o	Pressure handling options to test -  Minimum and average

•	Thermodynamic model – NRTL (Non-Random two liquid)

This NRTL model is used in DWSIM simulation because it accurately describes the non-ideal behaviour of methanol and water mixture. As this mixture deviates from ideal solution behaviour due to hydrogen bonding. 
The NRTL model ensures the accurate calculation of thermodynamic properties, which are critical for determining the outlet stream temperature, pressure and composition in mixer unit operation under minimum and average pressure handling options.

Simulation Objectives:
•	Calculate the outlet stream’s temperature, pressure and molar composition for minimum and average pressure handling options

•	Analyze the effect of pressure handling choice on the outlet stream properties. 
