# Minimum Distance Lasso for Robust Estimation in High-Dimensional Data

This project explores the **Minimum Distance Lasso (MD-Lasso)** method for robust regression in high-dimensional settings.  
MD-Lasso integrates minimum distance functionals into the Lasso framework to reduce the influence of outliers and improve model stability.

## Project Contents
- `MDlassoCode.ipynb` → Implementation of MD-Lasso, with comparisons to Lasso and Ridge regression.
- `Summary.pdf` → Research summary and simulation results.

## Methods
- Compared MD-Lasso, Lasso, and Ridge regression using simulated high-dimensional datasets.
- Used **gradient descent optimization** for parameter estimation.
- Evaluated models with **Mean Absolute Error (MAE)** and **Mean Squared Error (MSE)**.

## Results
- MD-Lasso produced more robust and accurate estimates than Lasso and Ridge in noisy, high-dimensional data.
- Demonstrated strong resilience to outliers.

## Tools & Libraries
- Python, Pandas, SciPy, Scikit-learn