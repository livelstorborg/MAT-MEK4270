# MAT-MEK4270: Numerical Methods for Partial Differential Equations

[![MAT-MEK4270 mandatory 1](https://github.com/livelstorborg/MAT-MEK4270/actions/workflows/mandatory1.yml/badge.svg?branch=main)](https://github.com/livelstorborg/MAT-MEK4270/actions/workflows/mandatory1.yml)


[![MAT-MEK4270 mandatory 2](https://github.com/livelstorborg/MAT-MEK4270/actions/workflows/mandatory2.yml/badge.svg?branch=main)](https://github.com/livelstorborg/MAT-MEK4270/actions/workflows/mandatory2.yml)

This repository contains mandatory assignments for MAT-MEK4270.

## Course Description

The course provides an introduction to numerical methods for partial differential equations (PDEs), including:
- Finite difference methods for elliptic, parabolic, and hyperbolic PDEs
- Spectral methods and the Galerkin method
- Stability analysis and convergence theory
- Implementation and applications of numerical schemes

Students learn both the theoretical foundations and practical implementation of numerical methods for solving PDEs that arise in physics, engineering, and applied mathematics.

## Mandatory Assignments

### [Mandatory 1](./mandatory1/)
**Finite Difference Methods for PDEs**
- Implementation of 2D wave equation solver (`Wave2D.py`)
- Solution of 2D Poisson equation (`poisson2d.py`)
- Analysis of stability and accuracy

### [Mandatory 2](./mandatory2/)
**Spectral Galerkin Methods**
- Implementation of Galerkin method framework (`galerkin.py`)
- Function approximation using orthogonal polynomials (Legendre, Chebyshev)
- Solving ODEs with various boundary conditions
- Trigonometric basis functions

## Repository Structure
```
MAT-MEK4270/
├── mandatory1/          # First mandatory assignment
│   ├── Wave2D.py
│   ├── poisson2d.py
│   └── report/
└── mandatory2/          # Second mandatory assignment
    └── galerkin.py
```