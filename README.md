# Regression Benchmark (Notebook Only)

This repository contains a Jupyter Notebook benchmarking several regression models across multiple datasets.

It is strictly an experimental evaluation setup — not a production project.

## What’s Inside

- K-Fold Cross Validation
- Basic preprocessing (scaling inside folds)
- Performance comparison:
  - MSE
  - MAE
  - R²
  - Training time
  - Inference time

## Models

- LinearRegression
- RandomForestRegressor
- MLPRegressor

## Datasets

- California Housing
- Diabetes
- Concrete Strength

Loaded directly from `scikit-learn` / `OpenML`.

## Notes

- No hyperparameter tuning
- No deployment code
- No packaging
- Notebook-based experiment only

Run the notebook sequentially to reproduce results.
