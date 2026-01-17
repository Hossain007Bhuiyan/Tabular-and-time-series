
`Numpy_linear_ridge_regression_california_housing.ipynb`

## Overview
This notebook implements a full regression workflow using **NumPy** for the core calculations:
- preprocessing
- linear regression (closed-form solution)
- ridge regression (L2 regularization)
- model validation using repeated hold-out

A key rule in the notebook text is: **do not use explicit for-loops** for the main NumPy-based tasks.

## What is implemented in the notebook
### 1) Preprocessing
- Custom train/test split
- Standardization (mean = 0, std = 1)
- Normalization (min-max scaling)

### 2) Linear regression
- Closed-form solution (normal equation)
- Prediction function
- Error metrics (RMSE and MAE)

### 3) Ridge regression (regularized linear regression)
- Closed-form ridge solution with alpha (regularization strength)

### 4) Model validation
- Repeated hold-out evaluation
- Ridge alpha scan and performance comparison

## Recommended outputs to save
Create and store these inside:
`assets/figures/`
- `rmse_vs_alpha.png` (ridge performance vs alpha)

## Setup
```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt

