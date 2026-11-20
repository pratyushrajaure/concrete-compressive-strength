# Concrete Compressive Strength Prediction

A Python machine learning project that predicts concrete compressive strength (MPa) using concrete mixture properties and curing age.

## Dataset

The dataset contains eight input features:

- Cement
- Blast Furnace Slag
- Fly Ash
- Water
- Superplasticizer
- Coarse Aggregate
- Fine Aggregate
- Age

**Target:** Concrete Compressive Strength (MPa)

## Models Implemented

- Mean Baseline
- Linear Regression (NumPy)
- Linear Regression (Scikit-learn)
- Ridge Regression
- Lasso Regression

Grid Search with 5-fold cross-validation was used to tune the Ridge and Lasso regularization parameters.

## Best Model Performance

Linear Regression achieved the best test performance:

| Metric | Result |
|---|---:|
| MAE | 8.895 MPa |
| RMSE | 11.191 MPa |
| R² | 0.580 |

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

## Execution

Run the concret.ipynb file

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Project Objective

To explore the application of machine learning in predicting concrete compressive strength and compare the performance of different regression techniques.