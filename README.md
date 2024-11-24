# Holt-Winters Forecasting Challenge

## Overview
This project demonstrates the application of the Holt-Winters (Triple Exponential Smoothing) model for time series forecasting. The project includes:
- Decomposition of time series into trend, seasonal, and residual components.
- Visualization of monthly and quarterly seasonality.
- Analysis using ACF and PACF plots.
- Model evaluation with metrics like MAE, RMSE, and MAPE.

## Dataset
- **File**: `airmiles.csv`
- **Description**: Contains monthly air passenger miles data.
- **Frequency**: Monthly data.

## Features
- Seasonal decomposition with `seasonal_decompose`.
- Visualization of trends and seasonal patterns.
- Implementation of the Holt-Winters method for forecasting.
- Model evaluation using multiple error metrics.

## Getting Started
### Prerequisites
- Python 3.8 or higher
- Libraries: `matplotlib`, `pandas`, `statsmodels`, `scikit-learn`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AdhamKhouly/holt-winters-forecasting-challenge.git
   cd holt-winters-forecasting
