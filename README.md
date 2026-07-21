<h1 align="center">
EES Models for the Thermoenergetic Analysis of Conventional and Modified Molten Salt Steam Generators (MSSG)
</h1>

## Overview

This repository contains the complete **Engineering Equation Solver (EES)** models developed for the numerical analyses presented in the manuscript:

**Optimization of Molten Salt Steam Generators for Enhanced Rankine Cycle Performance and Reduced Salt Flow in Solar Tower Plants**

The repository is provided as supplementary material to facilitate transparency, reproducibility, and future research related to the thermodynamic modeling of Molten Salt Steam Generators (MSSGs) for Solar Tower Power Plants.

## Repository Structure

| File | Description |
|------|-------------|
| **01_Rankine_Cycle_100MW_EES_Model.EES** | Thermodynamic model of a 100 MW regenerative Rankine cycle used as the reference power block. Includes turbines, condenser, feedwater heaters, deaerator, pumps, flash tank, drain cooler, and complete mass and energy balances. |
| **02_Conventional_MSSG_EES_Model.EES** | Numerical model of the conventional Molten Salt Steam Generator (MSSG) configuration, including the Superheater (SH), Reheater (RH), Evaporator (Evap), and Preheater (PH). Heat exchanger performance is evaluated using the effectiveness–NTU method. |
| **03_Modified_MSSG_SH1_EES_Model.EES** | Numerical model of the proposed MSSG configuration incorporating an additional Primary Superheater (SH1) and a Secondary Superheater (SH2). The model evaluates the thermoenergetic feasibility of producing steam at 16.7 MPa and 538 °C while reducing molten salt mass flow. |

## Software Requirements

The models were developed using:

- Engineering Equation Solver (EES)
- SI Unit System
- IAPWS Steam Property Library
- Solar Salt Property Library (60 wt.% NaNO₃ / 40 wt.% KNO₃)

## Model Features

The models include:

- Complete mass and energy balances
- Regenerative Rankine cycle analysis
- Steam property calculations using the IAPWS formulation
- Molten salt thermophysical property calculations
- Heat exchanger analysis based on the effectiveness–NTU method
- Thermal compatibility assessment
- Heat Rate calculation
- Thermal efficiency calculation
- Molten salt mass flow estimation
- Heat exchanger effectiveness, NTU, and UA calculations

## Design Conditions

| Parameter | Value |
|-----------|------:|
| Net Electrical Output | 100 MW |
| Main Steam Pressure | 16.7 MPa |
| Main Steam Temperature | 538 °C |
| Reheat Pressure | 2.5 MPa |
| Reheat Temperature | 538 °C |
| Heat Transfer Fluid | Solar Salt (60 wt.% NaNO₃ / 40 wt.% KNO₃) |


## Computational Workflow

```text
Reference Rankine Cycle Model
            │
            ▼
Conventional MSSG Model
            │
            ▼
Thermoenergetic Feasibility Assessment
            │
            ▼
Modified MSSG (SH1–SH2) Model
            │
            ▼
Performance Comparison
```

## Purpose

The purpose of this repository is to provide the complete EES implementation used in the numerical analyses reported in the associated publication.

The models allow researchers to reproduce the thermodynamic calculations, evaluate the conventional MSSG configuration, and analyze the proposed SH1-based configuration developed to overcome the thermoenergetic limitations associated with advanced steam conditions.

## Citation

If this repository contributes to your research, please cite the associated publication:
Garrido-Fayad, E. A., et al. *Optimization of Molten Salt Steam Generators for Enhanced Rankine Cycle Performance and Reduced Salt Flow in Solar Tower Plants*. Submitted to **Applied Thermal Engineering**.

## Author
**Enrique A. Garrido-Fayad**
Faculty of Engineering
Universidad Autónoma de Aguascalientes
Aguascalientes, Ags. Mexico


## License
This repository is made available for academic and research purposes.
© Enrique A. Garrido-Fayad. All rights reserved.
