# Long-Short Term Memory Model - Time Series Forecast

This project explores Bitcoin price using an LSTM model and technical analysis indicators. 

Tensorflow and Keras frameworks are adopted for the implementation.

> pip install tensorflow

The historical data can be accessed by installing yfinance library (https://pypi.org/project/yfinance/).

> pip install yfinance

## The Model

With the help of an LSTM network, we will try to predict the future price of Bitcoin. In order to do this, we used data a based on its price of the past 9 years and calculated technical analysis indicators. 

We will try predicting the adjusted close stock price of BTC based on the past N=60 days. One could try different values of N and see how precision of the forecasting algorithm changes with the length of the interval.

We start feature exploration with a simple univariate model, then gradually add more predictors into the model. We use RMSE test score and validation error to compare different models and their performance. By adding technical analysis indicators as new inputs the performance of the model performance improves. We should try running a trading rule based on this model. Upcoming!



<img width="658" alt="Screen Shot 2021-04-20 at 7 05 37 PM" src="https://user-images.githubusercontent.com/34326154/115470643-078eb680-a20d-11eb-9b27-3d1e54e1b434.png">
