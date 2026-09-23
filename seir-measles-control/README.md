# Optimal Control for Measles Outbreak (SEIR Model)

A numerical simulation project modeling the spread of measles using the SEIR (Susceptible-Exposed-Infected-Recovered) system of differential equations, extended with optimal control strategies.

## What it does

This project models how measles spreads through a population and simulates the effect of five different intervention strategies on controlling the outbreak:

- Vaccination
- Prophylactic treatment
- Immunoglobulin intervention
- Intensive treatment
- Quarantine

It compares the numerical solution of the disease spread **with** and **without** these control measures, to show how much each intervention reduces the spread of infection.

## Tech stack

- Python
- SymPy (symbolic mathematics, for deriving and solving the differential equation system)
- NumPy & Matplotlib (numerical computation and visualization)

## How to run

Open the notebook in Google Colab or Jupyter Notebook and run all cells in order. The notebook includes both the "without control" and "with control" simulations, followed by a comparison of results.

## Note

This project was originally developed as part of an Optimal Control Theory course project, applying differential equation modeling and optimal control theory to a real-world epidemiological problem.
