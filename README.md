# ARIMA-Time-Series
 Stationarity tests, Feature Engineering, Model Building, Evaluation

Check stationarity: If a time series has a trend or seasonality component, it must be made stationary before we can use ARIMA to forecast.

Difference: If the time series is not stationary, it needs to be stationarized through differencing. Take the first difference, then check for stationarity. Take as many differences as it takes. Make sure you check seasonal differencing as well.

Filter out a validation sample: This will be used to validate how accurate our model is. Use train test validation split to achieve this

Select AR and MA terms: Use the ACF and PACF to decide whether to include an AR term(s), MA term(s), or both.

Build the model: Build the model and set the number of periods to forecast to N (depends on your needs).

Validate model: Compare the predicted values to the actuals in the validation sample.
