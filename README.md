# Time-Series-Analysis
This project performs time series analysis on Ecuador's holiday events using the holidays_events.csv dataset. It visualizes trends and applies the ARIMA model to forecast future event patterns.
# 🗓️ Holiday Events Time Series Forecasting

This project analyzes and forecasts trends in Ecuador's national and regional holidays using time series techniques. It leverages the `holidays_events.csv` dataset (from a Kaggle competition) to understand seasonal patterns and build predictive models using ARIMA.

## 📊 Dataset Overview

The dataset includes:
- `date`: Date of the event (YYYY-MM-DD)
- `type`: Type of event (Holiday, Event, Transfer, etc.)
- `locale`: Level (Local, Regional, National)
- `locale_name`: Name of the affected location
- `description`: Event details
- `transferred`: If the holiday was moved from the actual calendar day


## 📌 Objectives

1. **Visualize Historical Event Trends**  
   - Frequency of events over time  
   - Seasonal spikes and trends

2. **Apply ARIMA for Forecasting**  
   - Use ARIMA to forecast the frequency of events over coming months  
   - Evaluate model using RMSE and MAPE

## 🛠️ Tools Used

- **Pandas** for data preprocessing  
- **Matplotlib** and **Seaborn** for visualization  
- **Statsmodels** for ARIMA forecasting  
- **Scikit-learn** for evaluation

## 📈 Output

- Trend plots of monthly event frequency  
- ARIMA-based forecast plot  
- Evaluation metrics: RMSE, MAPE  
- Discussion on event seasonality



