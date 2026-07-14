# Maths_Python

*Practice implementations of mathematical concepts translated into Python code, built alongside the course "Computational Physics: Scientific Programming with Python" by Dr. Börge Göbel.*

> **The core problem this repository addresses:** Mathematics on paper and mathematics in code look completely different. A Taylor series in a textbook is a sigma notation formula. In Python, it is a loop, an accumulator, and a convergence condition. This repository is the record of building that translation skill — from mathematical notation to working, runnable code.

---

## What This Repository Is

**Not a collection of finished projects. A learning record.**

Every file here represents one mathematical concept understood well enough to implement *from scratch* in Python — without copying, without a library doing the work underneath. The goal is to understand what the function is computing, not just that it computes it.

---

## Current Contents

### Series and Approximations

*   **Taylor Series — Exponential Function** (`taylor_exponential.py`): Implements the Taylor expansion of e^x from scratch using a manual summation loop. Compares the approximation against Python's `math.exp()` for increasing numbers of terms. Shows how the series converges toward the exact value as more terms are added.

---

## Planned Additions

As the course progresses, this repository will grow to include implementations of:

*   **Numerical Differentiation:** Forward, backward, and central difference methods; Error analysis versus step size *h*.
*   **Numerical Integration:** Riemann sums, trapezoidal rule, Simpson's rule; Gaussian quadrature.
*   **Differential Equations:** Euler method (implementation and error analysis); Runge-Kutta 4th order (RK4) from scratch; Comparison of Euler vs RK4 accuracy on the same problem; Applications including pendulum with damping and coupled oscillators.
*   **Linear Algebra & Eigenvalue Problems:** Gaussian elimination without library functions; LU decomposition; Eigenvalue computation for physical applications.
*   **Partial Differential Equations:** Heat equation in 1D and 2D; Wave equation.
*   **Monte Carlo Methods:** Random sampling and statistical physics applications.

---

## Related Repository

Physics simulations built using these mathematical tools live here: **[Python-Physics-Prototypes](https://github.com/Chakravarty-Vaibhav/Python-Physics-Prototypes)**

*The relationship between the two repositories:* This one is where the mathematics is learned. That one is where it gets applied to real physical systems — pendulum dynamics, orbital mechanics, drone flight simulation, and the Schwarzschild black hole geodesic project.

---

## Context

Second year B.Tech student at Thapar Institute of Engineering and Technology, building toward computational physics and scientific visualisation. Working toward a research project on numerical simulation of light geodesics in Schwarzschild curved spacetime. 

The mathematical methods in this repository are the foundation that makes the physics simulations in the companion repository work correctly.

**Built from first principles. No black boxes.**
