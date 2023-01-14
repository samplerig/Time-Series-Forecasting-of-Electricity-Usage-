# Time series Forecasting of Electricity Usage

Given electricity consumption data of the past, our goal here is to predict future electricity consumption. This is a time series forecasting problem.

I applied several statistical (ARIMA), machine learning (XGBoost) and deep learning (GRU) models to forecast electricity meter readings for 4 months to analyze consumption vs cost. No one model gave the best performance and instead completed each other. Thus, I created an ensemble using stacking, achieving an RMSE of 25.65.
