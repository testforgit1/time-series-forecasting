# Time Series Forecasting using ARIMA, LSTM, and Prophet

## Overview
This project implements time series forecasting on the monthly beer production dataset (1956-1995) using ARIMA (SARIMAX), LSTM, and Prophet models. It demonstrates data preprocessing, model comparison, and visualization to provide actionable insights for production trends.

## Project Details
- **Date**: August 2025 - October 2025
- **Dataset**: Monthly beer production in Australia (476 records)
- **Technologies**: Python, Pandas, NumPy, Statsmodels, Matplotlib
- **Performance**: Prophet model outperformed with lower RMSE on test data

## Features
- Exploratory Data Analysis (EDA) with seasonal decomposition and ACF/PACF plots.
- Implementation of SARIMAX for seasonal ARIMA, LSTM for deep learning, and Prophet for additive forecasting.
- Evaluation using RMSE and mean squared error on an 80/20 train-test split.
- Visualization of forecasts and trends using Matplotlib.

## Usage
- Run the Jupyter notebook `Time Series Forecasting using Arima, Lstm, Prophet.ipynb` to execute the analysis.
- Adjust parameters (e.g., train-test split) in the code as needed.

## Results
- Prophet model provided the best forecast accuracy, visualized for production trend insights.
- Suitable for supply chain optimization and demand forecasting applications.

## Challenges
- Handled missing values and ensured proper datetime conversion for time series analysis.
- Optimized LSTM model training for computational efficiency.

## Future Improvements
- Incorporate additional features (e.g., temperature, holidays) for Prophet.
- Expand dataset for more robust LSTM training.

## Contact
- Author: Yeshwanth Bikkavolu
- Email: yeswanthbikkavolu@gmail.com
- LinkedIn: linkedin.com/in/naga-veera-y-29379a2ba
