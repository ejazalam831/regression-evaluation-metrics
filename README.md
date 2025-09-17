# Loss Functions in Linear Regression: A Complete Guide

A comprehensive guide to understanding and implementing the five most important loss functions for regression models: MAE, MSE, RMSE, R-squared, and MAPE.

## Topics Covered

This notebook provides practical examples and clear explanations of:

- **Mean Absolute Error (MAE)** - Average prediction error in original units
- **Mean Squared Error (MSE)** - Penalizes large errors heavily
- **Root Mean Squared Error (RMSE)** - MSE in interpretable units
- **R-squared** - Proportion of variance explained by the model
- **Mean Absolute Percentage Error (MAPE)** - Percentage-based error metric


## Getting Started

### Prerequisites
```bash
pip install pandas numpy scikit-learn
```

### Running the Notebook
1. Clone this repository
2. Open `loss_functions_regression.ipynb` in Jupyter Notebook or Google Colab
3. Run all cells to see the examples in action

## Sample Data

The notebook uses a simple dataset of 5 restaurant tables with actual vs predicted tips:

| Table | Actual Tip | Predicted Tip |
|-------|------------|---------------|
| 1     | $4.00      | $3.50         |
| 2     | $6.00      | $5.80         |
| 3     | $2.00      | $2.90         |
| 4     | $8.00      | $7.20         |
| 5     | $3.50      | $3.10         |


## When to Use Each Metric

| Metric | Best For | Key Property |
|--------|----------|--------------|
| MAE | Easy interpretation, stakeholder communication | Robust to outliers |
| MSE | Model training, when large errors are costly | Heavily penalizes large errors |
| RMSE | Balance of interpretability and math properties | MSE in original units |
| R² | Model comparison, variance explanation | Shows proportion explained |
| MAPE | Business communication, scale-independent | Percentage-based results |


