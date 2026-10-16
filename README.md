# Gradient Descent for Linear Regression

A reproducible, beginner-friendly implementation of batch gradient descent
for linear regression. The notebook builds the estimator with NumPy, trains it
on synthetic data, and visualizes the fitted model and its convergence.

## Getting started

### Requirements

- Python 3.10 or newer
- Jupyter Notebook or JupyterLab

Install the dependencies:

```bash
python -m pip install -r requirements.txt
```

Launch Jupyter from the repository root and open `gradient_descent.ipynb`:

```bash
jupyter notebook
```

Run the notebook cells from top to bottom. A fixed random seed makes the
synthetic dataset reproducible.

## What the notebook covers

- Mean-squared-error objective and batch gradient updates
- A `GDRegressor` estimator for one or more numeric features
- Input validation, parameter estimation, and prediction
- Training metrics and visualizations for the fit and loss history

This is an educational implementation. For real-world modeling, use training
and validation/test splits, scale features when appropriate, and compare
results with a maintained machine-learning library.
