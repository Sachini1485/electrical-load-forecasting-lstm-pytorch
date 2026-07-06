# Electrical Load Forecasting Using LSTM with PyTorch

## Overview

This project implements a Long Short-Term Memory (LSTM) neural network using PyTorch to perform short-term electrical load forecasting.

The model predicts the next hour's electricity demand using the previous 24 hours of historical load data from the PJM Hourly Energy Consumption dataset.

---

## Features

- Data preprocessing
- Data normalization using MinMaxScaler
- Sequence generation
- LSTM implementation in PyTorch
- Model training and evaluation
- Next-hour load prediction
- Performance evaluation using MAE and RMSE
- Actual vs Predicted visualization

---

## Dataset

Dataset used:

**PJM Hourly Energy Consumption Dataset**

https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption

---

## Technologies Used

- Python
- PyTorch
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Project Workflow

1. Load Dataset
2. Data Preprocessing
3. Normalize Data
4. Create Time Sequences
5. Build LSTM Model
6. Train Model
7. Evaluate Performance
8. Predict Next Hour Load

---

## Performance Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## Results

The trained LSTM model successfully forecasts short-term electrical load by learning temporal patterns from historical electricity demand data.

---

## Author

Sachini M Thilakarathna
Electrical &Electeonic Engineerin

Your Name
