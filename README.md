# Data Science Projects by Jamael Codaye


## Regression/Forecasting
### [Monthly Peak Demand Forecasting for The Philippine Grid](https://github.com/Ma3ng/portfolio/blob/main/PHL_monthly_peak_demand_forecasting.ipynb)
  * Analysis and Forecasting of the monthly peak demand of the Luzon, Visayas, and Mindanao grid. Different ARIMA models are trained and ranked according to their AICC and test set MSE in order to chose the order of the paramters. Synthetic exogenous regressors are also added in order to account for the effect of the pandemic, particularly at the start of the pandemic. The model is then used to forecast 3 seasonal periods or years ahead in order to gain insight on the additional capacity needed of the grid.
### [Week Ahead Hourly Demand Forecasting for the Luzon Grid](https://github.com/Ma3ng/portfolio/blob/main/Week_ahead_electricity_forecast.ipynb)
   * The aim of this model is to forecast hourly week-ahead demand for the Luzon grids. The feature space of the model is divided into three categories, namely the trend, seasonal, and exogenous features. The model uses a linear trend and one-hot-encoded seasonal indicators for the trend and seasonal features. The exogenous features can be further divided into holiday and miscellaneous features. The effects of holidays are explored in the notebook in order to motivate their inclusion. The miscellaneous features are any time series data that we think is correlated with electricity demand such as temperature data and encomic data. The model is then tested on the test set and yielded a of MAPE 4.61% (361 MW Average Error).
### [Store Sales Forecasting (Kaggle Competetion)](https://github.com/Ma3ng/portfolio/blob/main/store-sales.ipynb)
   * This is my entry to the store sales forecasting competetion by kaggle. The notebook mainly explores linear regression models and AR models. Certain combination of the LR and AR models are explored. The difficulty in this project mainly lies in determining the heirarchy of the forecastint models, in my model, I used a separate model for each store and product family groups. The result is that an AR model with a single external regressor performed the best based on the submission score.
### [Temperature Forecasting]()
### [Monthly Peak Demand Forecasting for the Luzon Grid]()
## Classification
### [Credit Card Default Prediction]()
