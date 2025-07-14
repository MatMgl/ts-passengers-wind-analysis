# Time Series Analysis Project – ts-passengers-wind-analysis

This repository contains a project prepared for the course **Time Series Analysis**, carried out as part of university coursework.

## Project Tasks

**Task 1**  
Consider the monthly numbers of passengers (*file dane_RNKM3.csv*).  
Make numbers of passengers forecasts for each month of the first half of 2025.

**Task 2**  
Consider Mateusz’s time series from Lab 1 task 4.2 (i.e., wind speed in Delhi from 1st January 2013 to 1st January 2017).  
- Plot the periodogram. How can a periodogram be used to transform your data?  
- Make all necessary transformations to get a stationary time series (noise).  
- If possible, choose the ARMA (p, q) model for stationary noise.

## Tools & Methods Used

- **R language** (version 4.x)
- Time series modeling: `ts()`, `diff()`, `BoxCox.lambda()`, `acf()`, `pacf()`, `sarima()`
- Forecasting with ARIMA models (including ARIMA(p,d,q) fitting and prediction)
- Periodogram analysis using Fast Fourier Transform (FFT)
- Statistical tests:
  - Augmented Dickey-Fuller test (`adf.test()`)
  - Ljung-Box test (residual analysis)
- Visualization: `plot.ts()`, `monthplot()`, periodograms

## Project Report

The complete analysis, including plots and interpretation, is available in the following HTML report:

👉 [View the report](report/ts_project.html)

## Authors

- Sylwester Kubik
- Mateusz Mglej
- Aleksandra Rewera

*Year:* 2025

