# Geometric Brownian Motion Simulation in Python

This repository contains a Python implementation of **Geometric Brownian Motion (GBM)** — a commonly used model for simulating stock price paths in quantitative finance.

## 📁 File Description

- `Geometric_random_walk_implementation.py`: 
  - Simulates a stock price using the Geometric Brownian Motion formula.
  - Plots the simulated price path using `matplotlib`.

## 📈 What Is GBM?

Geometric Brownian Motion models a stock price \( S(t) \) as:

\[
S(t) = S(0) * exp(mu - 0.5 * sigma ** 2) * t + sigma * W(t)
\]

Where:
- \( S_0 \) is the initial stock price
- \( \mu \) is the expected return (drift)
- \( \sigma \) is the volatility
- \( W(t) \) is a standard Wiener process (Brownian motion)

## 🔧 How to Use

### Requirements
- Python 3
- `numpy`
- `matplotlib`

### Run the Simulation

```bash
python Geometric_random_walk_implementation.py
