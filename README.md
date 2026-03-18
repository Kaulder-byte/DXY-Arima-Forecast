# DXY-Arima-Forecast
Time-series forecasting of DXY using ARIMA with stationarity testing and out-of-sample evaluation
# DXY Forecasting using ARIMA

## Objective
To model and forecast the US Dollar Index (DXY) using ARIMA and evaluate predictive performance.

## Data
- Source: (Yahoo Finance or wherever)
- Frequency: Daily

## Methodology
- Stationarity test (ADF)
- Differencing
- ARIMA(p,d,q) selection
- Model fitting

## Results
- Forecast vs actual plot
- RMSE / error metric

##  Insights
- Model captures short-term trends but struggles with volatility spikes
- Suggestion: Combine with GARCH or exogenous variables

## Tools Used
- Python (pandas, statsmodels, matplotlib)
