# Day 22: Time Series Analysis & Forecasting

## The Concept
Time Series data is a sequence of data points collected at consistent time intervals. Unlike standard regression, the order of the data matters because past values often influence future ones. Forecasting is the act of using historical time series data to predict future values.

## Technical Terms
* Stationarity: A property where the mean and variance of the series do not change over time. Most models require the data to be "stationary" before processing.
* Trend: The long-term increase or decrease in the data (e.g., a general rise in global temperatures).
* Seasonality: Short-term regular patterns that repeat (e.g., increased ice cream sales every summer).
* Autoregression (AR): A model that uses the relationship between an observation and a number of lagged (past) observations.
* Moving Average (MA): A model that uses the dependency between an observation and a residual error from a moving average model applied to lagged observations.

## The "Golden Standard" Model: ARIMA
* ARIMA stands for AutoRegressive Integrated Moving Average. it is the most popular statistical method for time series forecasting.
* AR (Autoregression): Relationship between current and past values.
* I (Integrated): Differencing the data to make it stationary.
* MA (Moving Average): Handling the "shocks" or errors in the data.

## Real-World Scenario: E-commerce Inventory
Imagine you are managing stock for a large online store:
* The Problem: You don't want to run out of products, but you also don't want too much unsold stock in the warehouse.
* The Solution: You use Time Series Forecasting to look at the last 3 years of sales data.
* The Result: The model identifies a 20% "Seasonal" spike every November (Black Friday). You use this forecast to order extra stock exactly two weeks in advance.
