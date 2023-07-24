# Stock-Market-Prediction 📈
This project aims to predict stock prices using various time series forecasting models, including ARIMA (AutoRegressive Integrated Moving Average), FBProphet, Recurrent Neural Networks (RNNs), and Long-Short Term Memory (LSTM) models. The dataset used for training and testing the models is named "NIFTY50_all" and contains historical stock price data for various companies.

# Requirements
* python 3.x
* numpy
* pandas
* matplotlib
* seaborn
* sklearn
* tensorflow

# Models Explored
1. **ARIMA (AutoRegressive Integrated Moving Average)**: ARIMA is a time series forecasting method that models the relationship between an observation and its lagged values. It is suitable for stationary time series data and can provide insights into the data's autoregressive and moving average components.
2. **FBProphet**: FBProphet is a powerful time series forecasting tool designed to handle seasonality  in the data, making it useful for modeling stock price trends affected by time-dependent patterns.
3. **Recurrent Neural Networks (RNNs)**: RNNs are a class of neural networks that excel at processing sequential data. In this project, RNNs are explored for stock price prediction, taking advantage of their ability to capture temporal dependencies in the data.
4. **Long-Short Term Memory (LSTM) Models**: LSTM is a specialized type of RNN that addresses the vanishing gradient problem, making it well-suited for long-term dependencies in time series data. LSTM models are employed to further enhance the accuracy of stock price predictions.

# Model Evaluation
The performance of each model is evaluated using various metrics, such as mean squared error (MSE), mean absolute error (MAE), and root mean squared error (RMSE), to assess the accuracy of the stock price predictions.


