A gas-liquid separator is a device used in industrial processes to separate gas and liquid phases from a mixed stream. It is commonly employed in industries like oil and gas, chemical processing and power generation to ensure efficient operation by removing entrained liquid from gas stream or gases from liquid streams.
The separator unit in DWSIM can operate under specified conditions such as pressure and temperature or use inlet stream condition to perform the phase split. 

Aim: Design a gas-liquid separator in DWSIM to separate a natural gas stream containing methane, ethane, propane, and water into a dry gas stream (primarily methane and ethane) and a liquid stream (propane and water). 

Data: 	Inlet Stream Composition (molar basis): 
•	Methane (CH₄): 70 mol%

•	Ethane (C₂H₆): 20 mol%

•	Propane (C₃H₈): 8 mol%

•	Water (H₂O): 2 mol%

Inlet Stream Conditions: 

•	Flow rate: 1000 kmol/h

•	Temperature: 40°C

•	Pressure: 30 bar

 Separator Operating Conditions: 

•	Temperature: 25°C (to promote water condensation)

•	Pressure: 25 bar (slight pressure drop due to flashing

Thermodynamic model: Peng-Robinson, NRTL

NRTL model is used in DWSIM simulation because it accurately describes the non-ideal behaviour of methanol and water mixture. As this mixture deviates from ideal solution behaviour due to hydrogen bonding. 

Simulation Objectives: The goal is to determine the composition and flow rates of the vapor and liquid outlet streams and ensure effective separation of water from the gas phase to meet pipeline specifications.
