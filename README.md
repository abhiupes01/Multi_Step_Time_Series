# Airline_passanger_time_series
The repository is the implementation for predicting the time series flight data for a airlines. 
The prediction results mentioned here is based on the multistep forecasting with LSTM, Simple RNN, GRU and Autoregressive model

*Note : This repository illustrates the difference between the Sigle Step and Multi Step Time Series Forecasting*
*Most of the repository advocates the use of single step forcasting which is rather incorrect, as the value to be forecasted is selected from the historical data and the prediction from such forecast cannot be used for real case senario*
The analysis of prediction from time series is presented below. And from the given analysis it is evident that Autoregressive Model dominates the LSTM, GRU and Simple RNN in this case

## Simple RNN (Multi Step Forecasting)
![Show](https://i.postimg.cc/vmWN9HrM/mutli.jpg,rawimage=True)

## Simple RNN (Single Step Forecasting)
![Show](https://i.postimg.cc/YSdMg3ft/single.jpg,rawimage=True)
