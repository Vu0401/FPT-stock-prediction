# FPT Stock Prediction

## Overview
This project aims to predict the stock prices of FPT Corporation using deep learning models. The data is crawled using the `vnstock` library, and feature engineering is performed using `pandas-ta`. The project implements four types of deep learning models: Multi-Layer Perceptron (MLP), Recurrent Neural Network (RNN), Long Short-Term Memory (LSTM), and Bidirectional Long Short-Term Memory (Bi-LSTM).

## Data Collection
The stock data for FPT Corporation is automatically collected via the `vnstock` library, which provides an API to fetch historical stock price data from the Vietnam stock market.

## Models and Performance Metrics
The table below summarizes the performance of each model across various metrics:

| Model   | MAE   | MSE   | RMSE  | MAPE  |
|---------|-------|-------|-------|-------|
| MLP     | 0.032 | 0.017 | 0.024 | 0.030 |
| RNN     | 0.017 | 0.036 | 0.022 | 0.022 |
| LSTM    | 0.020 | 0.023 | 0.017 | 0.020 |
| Bi-LSTM | 0.010 | 0.013 | 0.010 | 0.021 |
