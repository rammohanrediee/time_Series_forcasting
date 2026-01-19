# Time Series Forecasting Projects

This repository contains Jupyter notebooks demonstrating time series analysis and forecasting techniques using real-world datasets. The projects focus on understanding temporal patterns, model assumptions, and forecast evaluation.

---

## Notebooks

### 1. forecasting.ipynb
A foundational notebook covering core time series concepts using Airline Passengers data, including:
- Data loading and preprocessing
- Exploratory Data Analysis (EDA)
- Trend and seasonality visualization
- Stationarity testing using the Augmented Dickey-Fuller (ADF) test
- Model comparison using ARIMA and SARIMA

**Key Results:**
- **RMSE:** 908.53
- **MAE:** 23.56

This notebook focuses on building intuition around classical time series methods.

---

### 2. MNC_forecasting.ipynb
An applied forecasting project using real-world financial data to predict **Apple (AAPL) Stock Prices**.

**Key steps include:**
- Fetching historical stock data using `yfinance`
- Time series visualization and trend analysis
- Model building using **ARIMA** (Statsmodels)
- Forecast evaluation

**New Financial Insights:**
- **Rolling Statistics:** Analysis of 30-day rolling mean and standard deviation to visualize trends and volatility.
- **Daily Returns:** Calculation and visualization of daily percentage changes.
- **Returns Distribution:** Histogram analysis of returns to understand risk profiles.
- **Cumulative Returns:** Tracking the growth of a hypothetical investment over time.

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- yfinance
- Statsmodels

---

## Key Takeaways

- Applied classical time series models to real datasets
- Evaluated forecasts using quantitative error metrics
- Gained practical experience in end-to-end time series modeling
- Analyzed financial metrics including volatility and cumulative returns
