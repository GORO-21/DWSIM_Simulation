A plug flow reactor, also known as continuous tubular reactor, is a type of chemical reactor where reactants flow through a cylindrical tube or pipe in a continuous, orderly manner, typically without mixing in axial direction. In PFR the residence time depends on the position of the reactor length. Reactant concentration decreases and product concentration increases along the length of the reactor as the reaction progresses. 

Aim: Simulate isomerisation of n-butane to iso-butane in a plug flow reactor (PFR) using DWSIM to achieve a conversion of at least 60%. 
Isobutane is a valuable product in petroleum industry, used as precursor for alkylation to produce high octane gasoline. The isomerization of n-butane is a reversible reaction, typically catalysed by solid catalyst (platinum on alumina), but for simplicity, we will model it for homogeneous kinetic reaction in gas phase. The CSTR operates isothermally to maintain consistent reaction conditions. 

Reaction:

The isomerization reaction is:

n-Butane↔Isobutane

•	Reaction Type: Homogeneous kinetic reaction (gas phase). 

•	Stoichiometry: n-Butane (-1), Isobutane (+1). 

•	Reaction Basis: Molar concentration (mol/L).

•	Rate Expression:

o	Forward: kf.[n-Butane]

o	Reverse: kr .[Isobutane]

o	Overall: kf.[n-Butane] - kr .[Isobutane]

•	Kinetic Parameters: 

o	Forward: Af = 5*10^6 s-1 , Ef= 50000 J/mol

o	Backward: Ar=4*10^6 s-1 , Er=55000 J/mol

•	Reaction Enthalpy: delta Hr = +8kJ/mol (endothermic) or is calculated by DWSIM

Data: 

Inlet Stream (single material stream): 

•	Feed Stream: 

o	Molar flow rate: 150 mol/h

o	Temperature: 100°C

o	Pressure: 2 atm

o	Composition: 100% n-Butane

• Reactor (PFR) Conditions: 

o	Operating mode: Isothermal at 100°C.

o	Pressure: 2 atm (negligible pressure drop).

o	Initial reactor volume: 5 m³ (adjust if needed to achieve ≥60% conversion).

•	 Outlet Stream: 

o	Single gas-phase product stream containing n-Butane and Isobutane.

o	Target n-Butane conversion: ≥60%.

•	Energy Stream: 

o	Represents heat load (kW) to maintain isothermal conditions at 150°C.
Thermodynamic Model:

•	Property Package: Peng-Robinson (Suitable for gas phase hydrocarbon systems)
