# Wind Speed Prediction with Interval Halving-Based Hyperparameter Optimization

A machine learning project predicting wind speed using several regression models, with hyperparameters optimized using the interval halving (bisection) method to minimize RMSE (Root Mean Squared Error).

## What it does

This project trains and compares multiple regression models including SVM, Gradient Boosting, KNN, and Random Forest to predict wind speed from environmental data. For each model, key hyperparameters are tuned using a bisection-based interval halving approach, narrowing down the optimal parameter range iteratively to minimize prediction error (RMSE).

## Tech stack

- Python
- scikit-learn (SVM, Gradient Boosting, KNN, Random Forest models)
- pandas & NumPy (data processing)
- Matplotlib & Seaborn (visualization)

## How to run

Open the notebook in Google Colab or Jupyter Notebook and run all cells in order.

## Note

This project was originally developed as part of a Non-Linear Programming course, applying the interval halving method (a numerical root-finding/optimization technique) to hyperparameter tuning in a machine learning context.
