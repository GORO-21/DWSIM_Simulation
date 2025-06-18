Shortcut Distillation in DWSIM is a simplified method for simulating distillation columns, used to estimate key design parameters for separating liquid mixture into their components based on difference in volatility. It’s a quick approach compared to rigorous distillation, ideal for preliminary column design. 
This shortcut distillation method relies on FenskeUnderwood-Gilliland correlation to calculate parameters like minimum number of stages, minimum reflux ratio and optimal feed stage location. 

Aim: Develop a simple process flow sheet to estimate distillate and bottom composition of a distillation column.

Data: 
100kmol/h of an equimolar mixture of benzene and toluene at 70°C and 1atm pressure, which is to be separated by staged distillation column. A reflux ratio of 3 is used. Composition of benzene in distillate should be 99% (by mol) toluene in the bottom should be 99% (mol). 
A total condenser and reboiler, both at 1 atm pressure are used. Determine the actual no. of stages, minimum reflux ratio and the minimum number of stages for the operation. 

DWSIM blocks used:
Shortcut Column
Material Streams
Energy Streams
Indicators

Thermodynamic Package:

UNIFAC – UNIFAC is Universal Functional Activity Coefficient, This method is widely used in chemical engineering for designing processes like distillation, extraction, and absorption, including shortcut distillation simulation in DWSIM.
This package is used when experimental data is limited particularly for non-ideal system and is used to predict phase behaviour and activity coefficient of liquid mixture. 
