# Wiener Process Simulation in Python

This repository contains a simple implementation of the **Wiener Process (or Brownian Motion)** using Python. The Wiener process is a fundamental concept in stochastic calculus and is widely used in quantitative finance, physics, and mathematics.

## 📁 File Overview

- `Wiener_process_implementation.py`: 
  - Simulates the Wiener process \( W(t) \) over time using cumulative sums of normally distributed random variables.
  - Plots the resulting path using Matplotlib.

## 📈 Output

The script generates and plots a single realization of a Wiener process using standard Brownian motion properties:

- \( W(0) = 0 \)
- Increments are independent and normally distributed \( N(0, dt) \)

## 🔧 Usage

1. Clone or download this repository.
2. Ensure you have Python and the following packages installed:
   - `numpy`
   - `matplotlib`
3. Run the script:

```bash
python Wiener_process_implementation.py
