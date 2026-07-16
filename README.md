# German Electricity Demand Forecasting using Time Series Models

## Overview

This project was completed as part of the MSc Data Science module **Time
Series Modelling Case Study**. The objective is to forecast German
electricity demand using historical electricity load data and compare
multiple forecasting approaches from statistical methods to deep
learning.

## Dataset

-   **Source:** Open Power System Data (OPSD)
-   Time period: January 2015 -- October 2020
-   Frequency: Hourly, Daily and Weekly

## Project Structure

``` text
Time_Series_Modelling_Case_Study/
├── Assignment_TSF.ipynb
├── time_series_60min_singleindex.csv
├── README.md
├── requirements.txt
├── figures/
└── report.pdf
```

## Models

-   Mean
-   Naive
-   Seasonal Naive
-   Drift
-   SARIMA
-   SARIMAX
-   Random Forest
-   LSTM

## Technologies

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Scikit-learn
-   Statsmodels
-   TensorFlow / Keras

## Installation

``` bash
git clone https://github.com/Manideepak077/Time_Series_Modelling_Case_Study.git
cd Time_Series_Modelling_Case_Study
pip install -r requirements.txt
```

## Results

  Model                     RMSE
  ---------------- -------------
  Mean                   4397.30
  Naive                  4459.11
  Drift                  5117.96
  Seasonal Naive         3006.76
  SARIMA                 9454.99
  SARIMAX                9771.54
  Random Forest          2541.47
  **LSTM**           **1019.24**

## Key Findings

-   Strong yearly seasonality in electricity demand.
-   Temperature improves forecasts as an exogenous variable.
-   Random Forest captures nonlinear relationships.
-   LSTM achieved the best forecasting performance.

## References

-   Open Power System Data (OPSD)
-   Hyndman & Athanasopoulos -- Forecasting: Principles and Practice
-   Breiman (2001) Random Forests
-   Hochreiter & Schmidhuber (1997) LSTM

## Author

**Soma Mani Deepak**\
MSc Data Science\
University of Hertfordshire

GitHub:
https://github.com/Manideepak077/Time_Series_Modelling_Case_Study
