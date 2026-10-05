# Fourth-Order Finite-Difference Approximation

This project investigates fourth-order numerical approximations of a second derivative using MATLAB and the Taylor-table method.

## Objective

The work derives and evaluates finite-difference approximations for the second derivative of the analytical function:

`f(x) = exp(x) cos(x)`

## Numerical Schemes

Three finite-difference formulations are investigated:

- Central difference
- Right-sided skewed difference
- Left-sided skewed difference

The finite-difference coefficients are derived using Taylor-series expansions and the Taylor-table method.

## MATLAB Analysis

The MATLAB implementation:

- evaluates the analytical second derivative
- calculates the numerical approximation
- varies the grid spacing `dx`
- calculates absolute error
- compares central and skewed schemes
- visualizes error using standard and log-log plots

## Key Observation

For the investigated function and grid spacings, the documented results show lower error for the central-difference scheme than for the skewed schemes.

Skewed schemes remain useful near boundaries where sufficient information is not available on both sides of the evaluation point.

## Engineering Relevance

The project demonstrates concepts relevant to numerical simulation and computational engineering, including:

- finite-difference discretization
- Taylor-series-based coefficient derivation
- boundary discretization
- truncation and numerical error assessment
- grid-spacing sensitivity

## Scope

This is an academic numerical-method exercise intended to demonstrate finite-difference derivation, MATLAB implementation, and numerical error comparison.
