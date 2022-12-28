# Energy-Consumption-Forecasting
## Auto Regression (AR):
- It uses past values to make a prediction
- https://github.com/pjborad/Energy-Consumption-Forecasting/blob/main/Energy%20Consumption%20Forecasting%20-%20AR.ipynb
## Moving Average (MA):
- It uses past errors to make a prediction
## Auto Regression Integrated Moving Average (ARIMA):
- It is the combination of AR and MA
- The only difference between ARMA and ARIMA is: ARIMA converts non-stationary series into stationary series
- It has three parameters (P,D,Q) where P is order of AR model, D is order of differencing to get stationary series, and Q is order of MA model
- https://github.com/pjborad/Energy-Consumption-Forecasting/blob/main/Energy%20Consumption%20Forecasting%20-%20ARIMA.ipynb
### These three models are statistics model to predict the future time-series. We can also use Machine Learning and Deep Learning algorithms like XGBoost, SVR, Decision Tree Regressor, LSTM, etc.
- https://github.com/pjborad/Energy-Consumption-Forecasting/blob/main/Energy%20Consumption%20Forecasting%20-%20XGBOOST.ipynb
- https://github.com/pjborad/Energy-Consumption-Forecasting/blob/main/Energy%20Consumption%20%20Forecasting%20-%20LSTM.ipynb
