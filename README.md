This is a time series analysis of Stock prices, I have used LSTM model here but stock market prediction can also be done with ARIMA model, the only drawback being, ARIMA requires the graph to be stationary and has low accuracy as compared to LSTM.
It uses LSTM model which predicts the stock closing price by training on the prices of previous days.
The Model's accuracy varies from stock to stock and the metric used is mean squared error.
Step is of 30 days
Data is provided by yahoo finance's python library yfinance
