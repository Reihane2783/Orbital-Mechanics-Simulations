# Orbital Mechanics Simulations in Python

A collection of Python simulations for studying orbital motion under gravitational forces and comparing different numerical integration methods.

## Overview

This repository explores the numerical simulation of celestial orbits using different physical models, initial conditions, and integration techniques.

The simulations investigate:

- Circular and elliptical orbital motion
- Sensitivity to initial velocity
- Modified gravitational force laws
- Orbital stability
- Numerical accuracy and stability
- Comparison of different integration methods

## Simulations

### 1. Circular Orbit Using Euler-Cromer

Simulates the orbital motion of Earth around the Sun using the Euler-Cromer integration method.

The model assumes an inverse-square gravitational force law.

- Circular initial orbit
- Euler-Cromer integration
- Newtonian gravitational interaction
- Visualization of orbital motion

### 2. Elliptical Orbit with Reduced Initial Velocity

Demonstrates how changing the initial tangential velocity affects the resulting orbit.

A reduced initial velocity produces an elliptical trajectory instead of a circular one, illustrating the sensitivity of orbital motion to initial conditions.

### 3. Orbital Motion with Different Gravitational Exponents

Investigates how modifying the distance dependence of the gravitational force affects orbital behavior.

The simulations compare:

- `n = 1.5`
- `n = 2.0`
- `n = 3.0`

where the gravitational force follows a generalized power-law dependence on distance.

The resulting trajectories are compared to study changes in orbital stability and closure.

### 4. Numerical Method Comparison

Compares different numerical integration methods for the same orbital system:

- Euler-Cromer
- Runge-Kutta 2nd order (RK2)
- Runge-Kutta 4th order (RK4)

The simulations use the same physical parameters and initial conditions to compare the resulting trajectories and numerical behavior.

## Physical Model

The simulations are based on Newtonian gravitational dynamics, with additional cases using generalized power-law force models.

The standard gravitational interaction follows an inverse-square dependence on distance.

## Numerical Methods

The repository demonstrates several approaches to solving the equations of motion numerically:

- Euler-Cromer integration
- Runge-Kutta 2nd order
- Runge-Kutta 4th order

The comparison illustrates how the choice of numerical method can affect orbital accuracy and stability.

## Visualizations

The simulations generate orbital trajectories that can be used to examine:

- Circular orbits
- Elliptical orbits
- Effects of initial conditions
- Effects of modified gravitational laws
- Differences between numerical integration methods

## Scientific Concepts

This project provides computational examples related to:

- Classical mechanics
- Orbital mechanics
- Newtonian gravitation
- Numerical integration
- Dynamical systems
- Numerical stability
- Initial-condition sensitivity

## Technologies

- Python
- NumPy
- Matplotlib
