Optimization of Molten Salt Steam Generators for Enhanced Rankine Cycle Performance and Reduced Salt Flow in Solar Tower Plants
Description
This repository contains the Engineering Equation Solver (EES) models developed for the research article:

Optimization of Molten Salt Steam Generators for Enhanced Rankine Cycle Performance and Reduced Salt Flow in Solar Tower Plants
The models were developed to evaluate conventional and modified molten salt steam generator (MSSG) configurations operating under advanced steam conditions representative of commercial subcritical Rankine power plants.

Repository Contents
File	Description
01_Rankine_Cycle_100MW_EES_Model.EES	Thermodynamic model of a 100 MW regenerative Rankine cycle including high-pressure turbine, reheater, condenser, feedwater heaters, deaerator, pumps, and mass and energy balances.
02_Conventional_MSSG_EES_Model.EES	Conventional molten salt steam generator (MSSG) model including Superheater (SH), Evaporator (Evap), Preheater (PH), and Reheater (RH). Heat exchanger sizing is based on the ε–NTU method.
03_Modified_MSSG_SH1_EES_Model.EES	Modified MSSG configuration incorporating an additional Primary Superheater (SH1) to improve thermal compatibility and achieve 16.7 MPa / 538 °C steam conditions. Heat exchanger sizing is performed using the ε–NTU method.

Software Requirements
•	Engineering Equation Solver (EES)
•	SI Unit System
•	IAPWS Steam Property Library
•	Molten Salt Property Library (60 wt.% NaNO₃ – 40 wt.% KNO₃)


Model Characteristics
The models include:
•	Mass and energy balances
•	Regenerative Rankine cycle
•	High-pressure and low-pressure feedwater heaters
•	Deaerator
•	Flash tank
•	Drain cooler
•	Turbine isentropic efficiencies
•	Pump efficiencies
•	Steam property calculations (IAPWS)
•	Molten salt thermophysical properties
•	Heat exchanger sizing using the effectiveness–NTU method
•	Thermal performance evaluation under design conditions

Design Conditions
•	Net electric output: 100 MW
•	Main steam pressure: 16.7 MPa
•	Main steam temperature: 538 °C
•	Reheat pressure: 2.5 MPa
•	Reheat temperature: 538 °C
•	Heat transfer fluid: Solar Salt (60 wt.% NaNO₃ / 40 wt.% KNO₃)
Purpose
These models were developed to investigate the thermodynamic feasibility of conventional and modified molten salt steam generator configurations for solar tower power plants operating under advanced steam conditions.
The modified configuration introduces an additional primary superheater (SH1), improving thermal compatibility between molten salt and water/steam while reducing the required molten salt mass flow.

Citation
If you use these models, please cite the corresponding publication:
Garrido-Fayad, E. A., et al. Optimization of Molten Salt Steam Generators for Enhanced Rankine Cycle Performance and Reduced Salt Flow in Solar Tower Plants. Submitted to Applied Thermal Engineering.

License
This repository is provided for academic and research purposes.
© Enrique A. Garrido-Fayad.
