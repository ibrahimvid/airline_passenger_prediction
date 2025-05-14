# Airline Passenger Prediction - Time Series Analysis

This repository demonstrates a complete time series analysis and forecasting workflow applied to the classic AirPassengers dataset. You will learn how to:
  - Load and preprocess time series data in Python
  - Visualize trends and seasonality
  - Test for stationarity and apply transformations
  - Decompose the series into trend, seasonal, and residual components
  - Build and evaluate ARIMA models for forecasting

## Repository Structure
```text
AirPassengers.csv                   # Monthly passenger counts (1949–1960)
timeseries-airlinepassengers.ipynb  # Jupyter Notebook with analysis and forecasting
README.md                           # This file
```

## Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- pandas
- numpy
- matplotlib
- statsmodels

You can install the required Python packages using pip:
```bash
pip install pandas numpy matplotlib statsmodels
```

## Getting Started
1. Clone this repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open **timeseries-airlinepassengers.ipynb** and run all cells to reproduce the analysis and forecasts.

## Dataset
The **AirPassengers.csv** file contains the monthly totals of international airline passengers from January 1949 to December 1960. It is a widely used benchmark dataset for time series modeling.

## Analysis Workflow
1. **Data Loading & Preprocessing**: Read CSV, parse dates, and create a time-indexed DataFrame.
2. **Exploratory Visualization**: Plot raw series to observe overall trends and seasonality.
3. **Stationarity Testing**: Use rolling statistics and the Augmented Dickey-Fuller test.
4. **Transformations**: Apply log transform and differencing to stabilize mean and variance.
5. **Decomposition**: Split the series into trend, seasonal, and residual components.
6. **ARIMA Modeling**: Fit ARIMA models, inspect diagnostics, and evaluate in-sample fit.
7. **Forecasting**: Predict future passenger volumes and visualize forecast against historical data.

## References
- Box, G. E. P., & Jenkins, G. M. (1976). *Time Series Analysis: Forecasting and Control*.
- https://www.statsmodels.org/

---
*This project is intended for educational purposes and demonstrates fundamental techniques in time series analysis.*