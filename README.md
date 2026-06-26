#  Time Series Forecasting Methods

A collection of time series analysis and forecasting assignments completed for the **IE0106 – Forecasting Methods and Applications** course, implemented in Python.

---

##  Repository Structure

```
├── term-project/       # SARIMAX forecasting on U.S. influenza data
├── assignment-1/       # Linear regression & exponential smoothing
├── assignment-2/       # Seasonal smoothing methods
└── README.md
```

---

##  Contents

###  Term Project — Influenza Positive Rate Forecasting
Time series analysis and 52-week forecasting of U.S. influenza positive rates (1997–2014).

- Data preprocessing & Cubic Spline Interpolation
- Seasonal decomposition, ACF/PACF analysis, ADF stationarity test
- Grid search for optimal ARIMA parameters based on AIC
- **Model:** SARIMAX(1,1,1)×(0,1,1,52)
- **MAE:** 1.1053 | **RMSE:** 1.6774

---

###  Assignment 1 — Regression & Exponential Smoothing

**Q1 — U.S. Motor Vehicle Fatalities (1966–2012)**
- Time series visualization and scatter plot analysis
- Simple linear regression with licensed drivers as predictor
- Residual analysis and Durbin-Watson test for autocorrelation

**Q2 — U.S. Unemployment Rate**
- Simple exponential smoothing with optimum λ
- Trend-adjusted exponential smoothing (Holt's method)
- First differencing and smoothing on first differences

---

###  Assignment 2 — Seasonal Smoothing Methods

**Q1 — International Sunspot Numbers**
- Time series visualization
- Simple exponential smoothing with optimal λ
- Evaluation of model adequacy for cyclical data

**Q2 — Monthly Soft Drink Demand**
- Seasonality verification via time series plot
- Winters' multiplicative method fitted on first 3 years
- One-step-ahead forecasts for the final 12 months with error analysis

---

##  Libraries Used

| Library | Purpose |
|---|---|
| `pandas` | Data manipulation |
| `numpy` | Numerical operations |
| `matplotlib` / `seaborn` | Visualization |
| `statsmodels` | SARIMAX, exponential smoothing, decomposition |
| `sklearn` | Regression modeling and error metrics |

---

##  Course Info

**Course:** Forecasting Methods and Applications  
**Department:** Industrial Engineering
