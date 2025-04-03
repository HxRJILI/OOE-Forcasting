# OOE-Forcasting
This repository contains the work done on Mitsui Morocco's production line data to analyze and forecast the daily Overall operations effectiveness (OOE). We leveraged statistical models and deep learning techniques to predict OOE, aiming to enhance decision-making and improve operational efficiency.
#  Methodology
### 1- Exploratory Data Analysis (EDA):
- Analyzed trends, correlations, and patterns in production data.
- Visualized OOE fluctuations over time.
### 2- Statistical Forecasting Models
To automate model selection and tuning, we used pmdarima, which optimized:
- Auto ARIMA
- SARIMA (Seasonal ARIMA)
- Exponential Smoothing (ETS)

### 3- Deep Learning Models
We experimented with various architectures to model temporal dependencies in OOE data:
- Recurrent models: LSTM, GRU, Vanilla RNN
- Hybrid models: CNN + LSTM, LSTM Autoencoder + Dense
- Advanced architectures: TCN (Temporal Convolutional Network)

### 4- Evaluation & Optimization:
- Compared model performance using MSE, RMSE, and R².
- Hyperparameter tuning and optimization strategies were applied.
