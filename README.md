# Demand Forecasting

Time series analysis of Brick and Mortar sales data

![ETS Model](https://github.com/abhinavahluwalia/Demand_Forecasting/blob/main/images/ETS_AAM.png "ETS time series model")

In this repository I explore times series forecasting methods and models for forecasting product demand.
Anticipating demand for products is a key requirement of any successful supply chain. Having an accurate estimate of demand can help an organization plan and control its supply chain to keep the customers happy with a certain degree of reliability. Unanticipated changes in demand can cause stress on the supply chain eventually leading to customer dissatisfaction and churn.

We will explore two different ways to forecast:

1. Time series analysis of the sales data - Studying the data with respect to itself over time. Forecasting is done using the following time series models:
* ETS Models
* ARIMA Models

2. Supervised learning - Use date time as features along with features derived from historical values of the data. Forecasting is performed using:
* Linear Regression Model
* LightGBM Model

The data used is obtained from https://www.kaggle.com/c/demand-forecasting-kernels-only/data which provides the sales data for brick and mortar stores.
