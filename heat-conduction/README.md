# 2D Heat Conduction

This project investigates numerical solutions of steady and unsteady two-dimensional heat conduction equations using MATLAB.

## Methods

The study includes:

- steady-state heat conduction
- transient heat conduction
- explicit and implicit formulations
- Jacobi iteration
- Gauss-Seidel iteration
- Successive Over-Relaxation (SOR)
- convergence using an absolute-error tolerance of `1e-4`

## Problem Setup

The documented case uses:

- Domain: 1 m × 1 m
- Grid: 10 × 10 nodes
- Top boundary: 600 K
- Bottom boundary: 900 K
- Left boundary: 400 K
- Right boundary: 800 K
- Thermal diffusivity: 1.1
- Relaxation factor: 1.1
- Time step: `1e-3`

## Numerical Comparison

For the investigated cases, the work compares the convergence behavior of Jacobi, Gauss-Seidel, and SOR iterative techniques.

The reported results show SOR requiring fewer iterations than Gauss-Seidel and Jacobi for the evaluated setup.

## Scope

This is an academic numerical-method exercise intended to demonstrate discretization, iterative solution techniques, convergence assessment, and temperature-field visualization.
