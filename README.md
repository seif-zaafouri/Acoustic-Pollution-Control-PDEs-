# Acoustic Pollution Control with PDEs

Numerical project studying **acoustic-wave control through partial differential equations and boundary-condition design**.

The code builds and solves complex-valued sparse systems on a 2D domain with **Dirichlet, Neumann and Robin boundary conditions**, including configurable absorbing boundaries and fractal geometries.

## Project overview

The pipeline is organised around three main stages:

1. **Pre-processing**
   - construction of the computational domain
   - definition of Dirichlet, Neumann and Robin boundaries
   - generation of fractal boundary geometries
   - preparation of PDE coefficients and source terms

2. **Numerical processing**
   - assembly of sparse complex-valued stiffness matrices
   - numerical solution of the acoustic field
   - handling of multiple boundary-condition types

3. **Post-processing**
   - visualisation of acoustic fields
   - error and energy analysis
   - comparison of boundary configurations

## Repository structure

```text
.
├── preprocessing.py             # Geometry and PDE setup
├── processing.py                # Sparse system assembly and numerical solve
├── postprocessing.py            # Analysis and visualisation
├── demo_control_polycopie2024.py
├── _env.py                      # Domain / boundary constants
├── fig_*.jpg                    # Numerical results
└── Rapport_EI.pdf               # Full project report
```

## Technical stack

- **Python**
- **NumPy**
- **SciPy sparse linear algebra**
- **Matplotlib**
- complex-valued numerical computation
- PDE modelling with mixed boundary conditions

## Results

The repository includes visualisations of the computed fields, numerical error and acoustic-energy quantities for different configurations.

➡️ [Full project report](Rapport_EI.pdf)

## Context

Academic numerical-modelling project carried out at **CentraleSupélec / Université Paris-Saclay**.
