# U.S. Security Yield Time Series Analysis and Forecasting



## Project Overview

This project analyzes the U.S. Security yield data from 1962 to 2024, utilizing time series analysis and econometric techniques to forecast future yields. The goal was to understand the stationarity, trends, and seasonality of the data and to apply various statistical models to predict the 5-year U.S. yield rate by the end of 2024.

## Key Learning Objectives
+ **Introduction to Time Series Analysis**: This project marked the first experience with time series analysis and econometric applications.
+ **Stationarity**: Gained a deep understanding of stationarity in time series and learned how to identify it using statistical tests like the Dickey-Fuller and KPSS tests.
+ **Trend and Seasonality Handling**: Explored methods to manage trends and seasonality in residuals.

## Methods and Techniques
1. **Data Preprocessing**:
+ Applied basic techniques like differencing and the Box-Cox method to achieve stationarity in the data.
2. **Model Selection**:
**ARIMA and SARIMA Models**: 
Utilized the auto_arima function to identify optimal model parameters, including seasonality, by analyzing autocorrelation functions (ACF). Determined a seasonal period of 24-27 months based on ACF results.
+ **Exponential Smoothing**: After the ARIMA model underperformed, switched to the Triple Exponential Smoothing (Holt-Winters Method) for a more reliable forecast.

## Forecasting Results
![image_alt](https://github.com/whistlesurprise/US-5Y-Yield-Forecasting/blob/57317568b7bbc448408003ce31132a88bc57d7e7/Screenshot%202024-10-22%20at%2022.59.16.png)
![image_alt](https://github.com/whistlesurprise/US-5Y-Yield-Forecasting/blob/654357e6abbf8558cb327f5348c5db58db467152/Screenshot%202024-10-22%20at%2022.32.05.png)
+ **Predicted 5-Year U.S. Yield Rate:** The final forecast predicted a 5-year U.S. yield rate of **3.43%** by December 31, 2024.
+ **Current Yield and Economic Indicators:** As of the current data, the yield stands at 3.90%, indicating that financial conditions have not eased, and there are no immediate signs of strong economic growth.
+ **Federal Reserve Projections:** Given the Federal Reserve's projections for two additional 25 basis point rate cuts in 2024, the forecast of 3.43% remains realistic.

## Conclusion


This project demonstrated the use of advanced time series forecasting techniques and provided a comprehensive understanding of handling large datasets, stationarity, and seasonality. The findings offer insights into the U.S. financial market outlook and yield forecasting for 2024.


