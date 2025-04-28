# Time-Series-Forecasting On Delayed Flights
**Problem Statement**:  
Forecast flight delays for the next 12 time periods using historical flight data.

**Data**:  
- Source: Provided delayed flight dataset (`DelayedFlights.csv`)
- Description: Includes flight numbers, departure/arrival delays, scheduled and actual times.

**Data Mining Operations**:  
- Data wrangling: Cleaned missing values, transformed date-time fields, indexed by time.
- Modeling: Built an ARIMA model after analyzing ACF/PACF plots and differencing for stationarity.
- Libraries: `pandas`, `matplotlib`, `statsmodels`
- Reason for model choice: ARIMA is effective for time series forecasting with autocorrelation patterns.

**Model Outputs**:  
- Visualized trends and seasonality.
- Generated a 12-step ahead forecast.
- Evaluated performance using MAE and RMSE.

**Limitations**:  
- Limited data history may impact long-term forecast stability.
- External factors affecting flight delays (e.g., weather) are not included.

**Were you able to effectively solve the problem?**  
Yes, the ARIMA model produced reasonable and statistically evaluated forecasts for future periods.
