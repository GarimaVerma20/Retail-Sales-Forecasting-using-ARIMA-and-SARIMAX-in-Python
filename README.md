# Retail-Sales-Forecasting-using-ARIMA-and-SARIMAX-in-Python

This project presents a comprehensive time series analysis and forecasting of retail sales for a brick-and-mortar store. Using historical data from 2000 to 2015, the project explores trends, seasonality, and other time series components to predict future sales and support strategic decision-making.

## Problem Statement
The retail industry thrives on accurate demand forecasting to manage inventory and maximize profits. This project aims to forecast sales for a physical retail store using historical sales data. The analysis applies statistical and machine learning models, focusing on ARIMA and SARIMAX, to achieve accurate predictions.

## Objectives
1. Perform **Exploratory Data Analysis (EDA)** to understand sales trends and seasonality.
2. Build and compare **ARIMA** and **SARIMAX** models for forecasting.
3. Evaluate model performance using **RMSE** and **AIC** metrics.
4. Provide actionable insights for better sales planning.

## Methodology
### 1. Data Preparation
- Preprocessed historical sales data.
- Split the data into training and testing sets.

### 2. Exploratory Data Analysis
- Analyzed time series components, including trends, seasonality, and residuals.
- Visualized sales data with line plots and decompositions.

### 3. Forecasting Models
#### ARIMA (AutoRegressive Integrated Moving Average)
- Built ARIMA models with parameter tuning based on ACF and PACF plots.
- Evaluated models using AIC to identify the best fit.

#### SARIMAX (Seasonal ARIMA with Exogenous Variables)
- Extended the ARIMA model to include seasonal components and external variables.
- Compared the performance of SARIMAX against simpler ARIMA models.

### 4. Model Evaluation
- Used **Root Mean Squared Error (RMSE)** to evaluate prediction accuracy.
- Compared models based on AIC values and residual diagnostic plots.

### 5. Forecasting
- Predicted sales for the test data and generated future forecasts with confidence intervals.

## Key Results
- **ARIMA Models**: Provided reliable forecasts based on historical patterns.
- **SARIMAX Models**: Improved accuracy by incorporating seasonality and exogenous variables.
- Best models demonstrated low RMSE, indicating precise predictions.

## Tools and Libraries
- **Python**: pandas, numpy, matplotlib, seaborn
- **Forecasting Models**: statsmodels (ARIMA, SARIMAX)
- **Evaluation Metrics**: Root Mean Squared Error (RMSE), Akaike Information Criteria (AIC)

