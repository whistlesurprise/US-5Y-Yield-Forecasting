In this project, I analyzed a time series consisting of U.S. Security yield data from 1962 to 2024. This was my first experience with time series analysis and econometric applications. I learned about stationarity in time series and how to identify it using various statistical tests, such as the Dickey-Fuller and KPSS tests. Additionally, I explored methods for handling trends and seasonality in residuals.

I applied basic techniques like differencing and the Box-Cox method to achieve stationarity in the data. To forecast future yields, I delved into ARIMA and SARIMA models, utilizing auto_arima to identify the most optimal model parameters, including seasonality, by analyzing autocorrelation functions (ACF). I determined a seasonal period of 24-27 months based on ACF results; however, the ARIMA model did not perform as well as expected. Consequently, I chose a simpler approach using Exponential Smoothing, specifically the Triple Exponential Smoothing Holt-Winters Method.

As an outcome, my analysis forecasted a 5-year U.S. yield rate of **3.43% for December 31, 2024**. The current yield is **3.81%**, largely driven by inflationary pressures due to market expectations of strong economic growth. However, considering the Federal Reserve has projected **two additional 25 basis point rate cuts** in 2024, my forecast of **3.43%** appears realistic by the end of 2024
