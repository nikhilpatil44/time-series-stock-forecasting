
# Apple stock price prediction using LSTM Neural Network

A long short-term memory network (LSTM) is one of the most commonly used neural networks for time series analysis. The ability of LSTM to remember previous information makes it ideal for such tasks. In this article, we saw how we can use LSTM for the Apple stock price prediction.


# Dataset
The dataset is taken from yahoo finace's website. The dataset consists of Open, High, Low and Closing Prices of Apple Inc. stocks from 1st January 2001 to 26th July 2021 - total 5162 rows.


# Price Indicator
Stock traders mainly use three indicators for prediction: OHLC average (average of Open, High, Low and Closing Prices), HLC average (average of High, Low and Closing Prices) and Closing price, In this project, Closing Price has been used.


# Model 
Four sequential LSTM layers have been stacked together and one dense layer is used to build the RNN model using Keras deep learning library. Since this is a regression task, 'mean_squared_error' is used for loss and 'adam' optimizer is used for compilation.
