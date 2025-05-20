# Exchange_Rate_Prediciton
Overview
This project provides a clean, end-to-end pipeline for forecasting exchange rates using historical data. It demonstrates data cleaning, feature engineering, model training with XGBoost, evaluation, and visualization of results — all designed for time series data like currency exchange rates.

Features
Data Preparation:
Converts date columns to datetime format.
Ensures exchange rate data is numeric and handles missing values gracefully.
Sorts data chronologically to maintain time order integrity.

Feature Engineering:
Creates lag features to capture past values (lags 1 to 3).
Calculates moving averages (3-day and 7-day) to capture trends and smooth noise.
Defines the target variable as the next day’s price for forecasting.

Modeling:
Uses XGBoost regressor — a powerful, gradient boosting tree-based model optimized for tabular data.
Hyperparameters are set for balanced learning and to reduce overfitting.

Evaluation:
Uses Mean Absolute Error (MAE) to quantify prediction accuracy.
Visualizes actual vs. predicted prices over time to assess model performance visually.

How to Use
Prepare your dataset with at least Date and Rate columns.
Run the script to preprocess data, engineer features, train the model, and generate predictions.
Review printed evaluation metrics and generated plots for insights.

Summary
This project offers a solid foundation for time series forecasting with exchange rate data, combining essential data science steps with a robust predictive model. 

