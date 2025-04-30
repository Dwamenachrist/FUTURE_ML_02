# FUTURE_ML_02

# Stock Price Forecasting with LSTM

A deep learning project to predict stock prices using LSTM networks and historical data.

## Description
This project uses an LSTM model to forecast stock prices based on past data and technical indicators like EMA and MACD. It’s simple to use and provides clear visualizations of predictions.

## Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/Dwamenachrist/FUTURE_ML_02.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   *Needs Python 3.8+ and libraries like `yfinance`, `tensorflow`, and `pandas`.*

## Usage
1. Get stock data:
   ```python
   price_data = fetch_and_prepare_data('NVDA', '2016-01-01', '2024-01-01')
   ```
2. Train the model:
   ```python
   history = model.fit(train_inputs, train_targets, epochs=50, batch_size=32)
   ```
3. See results:
   ```python
   visualize_forecast(real_prices, forecasted_prices, 'NVDA')
   ```
