# Time Series Forecasting with LSTM Neural Network

A deep learning project that predicts future values in a time series dataset for the next 20 time steps, using an LSTM (Long Short-Term Memory) neural network.

## What it does

This project builds and trains an LSTM model (a type of neural network well-suited for sequential/time series data) to forecast future values based on historical data patterns. The workflow includes:

- Data preprocessing and normalization (using MinMaxScaler)
- Building and training an LSTM model with TensorFlow/Keras
- Evaluating model performance using test data
- Forecasting 20 future time steps and comparing predictions against actual values using MAE (Mean Absolute Error) and MSE (Mean Squared Error)

## Tech stack

- Python
- TensorFlow / Keras (LSTM model)
- pandas & NumPy (data processing)
- scikit-learn (data scaling & evaluation metrics)
- Matplotlib (visualization)

## How to run

Open the notebook in Google Colab or Jupyter Notebook, make sure the dataset file is available in the working directory, then run all cells in order.

## Note

This project was originally developed as a course assignment for Capita Selecta for Applied Mathematics, applying neural network-based time series forecasting to a given dataset.
