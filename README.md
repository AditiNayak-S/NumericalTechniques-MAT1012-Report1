# Numerical Analysis and Algorithmic Methods — Part 1: Theoretical Framework

This repository contains the first part of the laboratory notebook sequence, focusing entirely on the theoretical and mathematical foundations governing core numerical routines. This document establishes the analytical framework necessary to understand, derive, and validate the computational models implemented in subsequent phases.

## Core Characteristics

* **Theoretical Focus:** A rigorous analysis of mathematical derivations, convergence proofs, and error bounds without code overhead.
* **Structural Discretization:** Detailed breakdowns of how continuous mathematical models are mapped into discrete spaces using step-size parameterization ($h$).
* **Analytical Validation:** Comprehensive frameworks for evaluating algorithm stability limits, including relaxation parameters and the Courant-Friedrichs-Lewy (CFL) condition.

---

## Theoretical Roadmap

The framework systematically details the underlying mathematics of 15 core numerical experiments:

### 1. Root Optimization and Boundary Analysis
* **Generalized Newton's Method:** Analytical adjustment strategies for handling multiple roots to restore quadratic convergence profiles.
* **Finite Difference Approximations:** Taylor series expansions establishing truncation errors for Forward, Backward, and Central difference formulas.

### 2. Interpolation and Polynomial Approximation
* **Equally Spaced Formulations:** Theoretical derivations of Newton’s (Forward/Backward), Gauss (Forward/Backward), and Stirling’s central difference interpolating polynomials.
* **Unequally Spaced Formulations:** Structural mechanics of Lagrange’s interpolation polynomial and Inverse Interpolation frameworks.

### 3. Statistical Linearization
* **Regression Analysis:** Mathematical optimization using least-squares criteria to linearize and fit power ($y = ax^b$) and exponential ($y = ae^{bx}$) function trends.

### 4. Numerical Calculus and Differential Equations
* **Quadrature Formulations:** Derivations of Newton-Cotes integration formulas, including the Trapezoidal Rule and Simpson’s (1/3 and 3/8) geometric bounds.
* **Ordinary Differential Equations:** Stability analyses of single-step marching methods, contrasting the Predictor-Corrector Modified Euler method with 4th-Order Runge-Kutta (RK4) truncation limits.

### 5. Governing Partial Differential Equation Stencils
* **Parabolic Systems (Heat Equation):** Stability analysis of the explicit Forward-Time Central-Space (FTCS) finite-difference mesh system.
* **Hyperbolic Systems (Wave Equation):** Mathematical formulation of wave propagation bounds and the enforcement of the CFL stability criterion.
* **Elliptic Systems (Laplace Equation):** Convergence theory of static fields utilizing the 4-Point Liebmann Stencil and Gauss-Seidel relaxation math.
