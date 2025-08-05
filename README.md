# TimeSeries-Fund-Price-Forecasting-ARIMA

# Time Series Fund Price Forecasting using ARIMA

This project demonstrates how to forecast fund prices using time series analysis and ARIMA models in Python. It includes data preprocessing, exploratory analysis, stationarity checks, model fitting, evaluation, and forecasting—all in a Jupyter Notebook.

## 📈 Features

- Fetches historical fund price data (using [yfinance](https://github.com/ranaroussi/yfinance))
- Performs data cleaning and visualization
- Checks for stationarity (ADF test) and applies differencing
- Uses ACF/PACF plots to select ARIMA parameters
- Trains and tests ARIMA model
- Evaluates performance (RMSE)
- Plots forecasts with confidence intervals

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- The following Python packages:
  - pandas
  - numpy
  - matplotlib
  - yfinance
  - statsmodels
  - scikit-learn

You can install the dependencies with:
```bash
pip install pandas numpy matplotlib yfinance statsmodels scikit-learn
