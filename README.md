# Optimization of Molten Salt Steam Generators for Enhanced Rankine Cycle Performance and Reduced Salt Flow in Solar Tower Plants

## Description

This repository contains the **Engineering Equation Solver (EES)** models developed for the research article:

> **Optimization of Molten Salt Steam Generators for Enhanced Rankine Cycle Performance and Reduced Salt Flow in Solar Tower Plants**

The models were developed to evaluate conventional and modified **Molten Salt Steam Generator (MSSG)** configurations operating under advanced steam conditions representative of commercial subcritical Rankine power plants.

---

## Repository Contents

| File | Description |
|------|-------------|
| **01_Rankine_Cycle_100MW_EES_Model.EES** | Thermodynamic model of a 100 MW regenerative Rankine cycle including turbines, pumps, feedwater heaters, condenser, reheater, deaerator, flash tank, and complete mass and energy balances. |
| **02_Conventional_MSSG_EES_Model.EES** | Conventional Molten Salt Steam Generator (MSSG) model including Superheater (SH), Reheater (RH), Evaporator (Evap), and Preheater (PH). Heat exchanger analysis is performed using the effectiveness–NTU method. |
| **03_Modified_MSSG_SH1_EES_Model.EES** | Proposed MSSG configuration incorporating an additional Primary Superheater (SH1) and Secondary Superheater (SH2) to improve thermal compatibility and achieve advanced steam conditions. Heat exchanger sizing is performed using the effectiveness–NTU method. |

---

## Software Requirements

- Engineering Equation Solver (EES)
- SI Unit System
- IAPWS Steam Property Library
- Molten Salt Property Library (60 wt.% NaNO₃ / 40 wt.% KNO₃)

---

## Model Features

The models include:

- Complete mass and energy balances
- Regenerative Rankine cycle
- High- and low-pressure feedwater heaters
- Deaerator
- Flash tank
- Drain cooler
- Steam turbine expansion
- Pump performance
- Thermophysical properties from the IAPWS formulation
- Thermophysical properties of molten salt
- Heat exchanger modeling using the effectiveness–NTU method
- Thermal compatibility assessment
- Heat Rate calculation
- Thermal efficiency calculation
- Molten salt mass flow calculation

---

## Design Conditions

| Parameter | Value |
|-----------|------:|
| Net Power Output | 100 MW |
| Main Steam Pressure | 16.7 MPa |
| Main Steam Temperature | 538 °C |
| Reheat Pressure | 2.5 MPa |
| Reheat Temperature | 538 °C |
| Heat Transfer Fluid | Solar Salt (60 wt.% NaNO₃ / 40 wt.% KNO₃) |

---

## Repository Workflow

```text
100 MW Rankine Cycle Model
            │
            ▼
 Conventional MSSG Model
            │
            ▼
 Thermal Feasibility Assessment
            │
            ▼
 Modified MSSG (SH1) Model
            │
            ▼
 Performance Comparison
```

---

## Purpose

The objective of this repository is to provide the complete EES implementation used to evaluate the thermodynamic feasibility of conventional and modified Molten Salt Steam Generator (MSSG) configurations for solar tower power plants operating under advanced steam conditions.

The proposed configuration introduces an additional Primary Superheater (SH1), improving thermal compatibility between molten salt and the water–steam cycle while reducing the required molten salt mass flow.

---

## Citation

If these models are used in academic research, please cite the corresponding publication:

> Garrido-Fayad, E. A., et al. **Optimization of Molten Salt Steam Generators for Enhanced Rankine Cycle Performance and Reduced Salt Flow in Solar Tower Plants.** *Applied Thermal Engineering* (submitted).

---

## Authors

**Enrique A. Garrido-Fayad**

Department of Mechanical Engineering

Universidad Autónoma de Aguascalientes

Aguascalientes, México

---

## License

This repository is provided for **research and academic purposes**.

© Enrique A. Garrido-Fayad. All rights reserved.
