# Gridded-ion-thruster-0D-model
0D global model of a Krypton gridded ion thruster developed for an IPSA Master's project. The model estimates ion beam velocity, thrust, and propulsion efficiencies using a simplified plasma approach implemented in Python.

## Author
Gabriel Casarotto  
IPSA – Institut Polytechnique des Sciences Avancées  
January 2026

## Project Description

The model represents the thruster using a **0D global plasma approach**, where averaged quantities inside the discharge chamber are considered.  

The discharge plasma is assumed to already exist, and the model focuses primarily on the **ion beam extraction and propulsion performance**.

Key aspects modeled include:

- Ion production from injected propellant
- Ion beam acceleration through electrostatic grids
- Mass utilization efficiency
- Electrical efficiency
- Thrust estimation

The propellant considered in the model is **Krypton**.

## Repository Structure
├── 0D_GIT.ipynb # Python notebook containing the global model implementation \n
├── equations.pdf # Summary of the physical equations used in the model
└── README.md


## Model Characteristics

The implemented model estimates several key propulsion parameters:

- **Mass utilization efficiency (η_mass)**  
  Fraction of injected propellant that becomes ionized.

- **Ion efficiency (η_ion)**  
  Fraction of injected propellant that contributes directly to thrust.

- **Electrical efficiency (η_elec)**  
  Conversion efficiency from electrical power to kinetic energy of the ion beam.

- **Thrust**

- **Beam velocity**

## Tools and Libraries

The model is implemented in **Python** and relies on:

- `NumPy`
- `SciPy`
- `Matplotlib`

## Notes

This simplified model is intended for **educational and conceptual analysis purposes** and does not represent a full plasma simulation.

It provides a first-order estimation of the performance of a **gridded ion propulsion system**.
