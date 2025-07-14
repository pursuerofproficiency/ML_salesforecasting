# sales_forecasting
Sales forecasting using multiple models - Seasonal Naïve, Holt-Winters, ARIMA, SARIMA and Linear Regression Model

## Project Objective
The goal of this project was to apply a range of quantitative forecasting techniques, including time series and causal models, to predict future product sales. The dataset contained historical sales data with noticeable trends and seasonality, making it an ideal candidate for testing different model types.

## Key steps in the project included:

Performing time series analysis to explore trends, seasonality, and stationarity

Training multiple forecasting models on the training dataset

Evaluating performance and selecting the best model based on predictive accuracy

## Models Implemented
To ensure a well-rounded comparison, I implemented several models across different forecasting approaches:

Seasonal Naïve Model - a simple benchmark that assumes seasonal patterns repeat

Holt-Winters Model (Triple Exponential Smoothing) - useful for capturing trend and seasonality

ARIMA and SARIMA Models - flexible statistical models for autocorrelated data

Linear Regression Model - using time and seasonal indicators as predictors

Each model was evaluated using error metrics such as RMSE to assess how well it forecasted unseen data.

## Conclusion
After testing multiple forecasting techniques, the linear regression model emerged as the most effective in this specific case. The dataset exhibited a clear linear trend and strong seasonality, which the regression model was able to capture effectively through time-based and seasonal features.

This result highlights that even with complex time series data, simpler models can often perform just as well — or even better — when the data structure aligns with their assumptions. In this case, a regression approach not only offered solid performance but also provided a more interpretable and scalable solution.
