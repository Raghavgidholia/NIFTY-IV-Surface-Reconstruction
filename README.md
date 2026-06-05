# NIFTY IV Surface Reconstruction

## Overview

This project focuses on reconstructing missing implied volatility (IV) values from a NIFTY option chain dataset.

The solution combines:

* Linear interpolation baseline
* Log-moneyness transformation
* ATM-weighted polynomial smile fitting
* Hybrid wing extrapolation
* Temporal fallback interpolation

## Methodology

1. Data exploration and missing value analysis
2. Linear interpolation benchmark
3. Volatility smile modeling
4. ATM-weighted polynomial fitting
5. Hybrid reconstruction of interior and wing strikes
6. Temporal interpolation for unresolved values

## Results

* Public Leaderboard Rank: 16
* Public Score: 0.000039128

## Repository Contents

* `NIFTY_IV_Surface_Reconstruction_Top20_Solution.ipynb`
* `submission_top20_solution.csv`
* `README.md`

