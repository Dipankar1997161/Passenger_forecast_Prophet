# Passenger_forecast_Prophet


## Overview
The following repo used facebook's Prophet tool for Time-series forecasting

Time series forecasting occurs when you make scientific predictions based on time-stamped historical data. It involves building patterns through historical analysis and using them to observe and guide future strategic decision making. An important difference in forecasting is that at working time, future outcomes are not available at all and can only be estimated by careful analysis and evidence-based predictions.
Time Series Forecasting involves making assumptions and interpretations about given data. Time series forecasting using the best-fit model needed to predict future observations based on complex processing of current and previous data
![image](https://user-images.githubusercontent.com/85514219/225669603-f5647993-a0fc-4199-86dd-d4e595cf7669.png)


## Dependencies:
    Pandas
    Fbprophet
    
## Installation
    pip install pystan
    pip install fbprophet

If this doesn't work, use the following installation command
    
    conda install -c conda-forge fbprophet

## Prophet
Prophet follows the sklearn model API. We create an instance of the Prophet class and then call its matching and predictive methods.

The Prophet input is always a two-column dataframe:
ds and y. The ds (data stamp) column should be in the format that Pandas expects, ideally YYYY-MM-DD for a date or YYYY-MM-DD HH:MM:SS for timestamp. The y column should be numeric and represent the metric we want to predict.
