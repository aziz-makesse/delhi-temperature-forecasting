## Multivariate Weather Forecasting using RNN & LSTM
This project uses Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) models to perform multivariate time series forecasting on weather data from Delhi. The dataset contains daily observations of temperature, humidity, wind speed, and pressure.

---

## Key Features
- Dataset: Daily Delhi Climate

- Models:

  - SimpleRNN for baseline performance

  - LSTM for improved temporal learning

- Input shape: sequences of 50 time steps with 4 features

- Target: prediction of all 4 weather parameters for the next day

---

## Metrics
Models are trained using Mean Squared Error (MSE) and evaluated on a held-out test set.
