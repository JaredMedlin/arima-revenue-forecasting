# ARIMA Revenue Forecasting

**WGU MSDA D213 | Jared Medlin | November 2025**

## Overview

A time series analysis using ARIMA to forecast telecom revenue 90 days into 
the future, based on 731 days of daily revenue data.

## Research Question

Can an ARIMA model reliably forecast revenue trends from historical daily data?

## Key Results

- Auto ARIMA selected model order (1,1,0) — one autoregressive lag, 
  one differencing step, no moving average term
- No seasonality detected via periodogram, ACF, or spectral density analysis
- 90-day forecast continues the existing upward trend
- Relative error: ~37.3% (RMSE / mean), indicating a weak but directionally 
  useful model

## Tools & Methods

- **Language:** Python 3 (Jupyter Notebook)
- **Libraries:** pandas, statsmodels, pmdarima, scipy, matplotlib
- **Techniques:** ADF stationarity test, ACF/PACF analysis, periodogram, 
  spectral density, time series decomposition, Auto ARIMA, 80/20 train-test split

## Repository Contents

| File | Description |
|------|-------------|
| `JaredMedlinD213Task1.pdf` | Full written analysis report |
| `D213Task1(4).ipynb` | Jupyter Notebook with code and outputs |
| `data/` | Training and test datasets plus raw data |
