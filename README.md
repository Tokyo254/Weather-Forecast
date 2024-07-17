# Weather-Forecast
Weather parameters forecast by applying ARIMA model in order to accurately predict the parameters of temperature, relative
humidity, wind gusts, and wind direction. 
To forecast the weather parameters, we first checked for missing values and performed a non-parametric interpolation “spline” to impute the missing values. Later on, we sought to reduce the number of observations by selecting the fifth observation from our series because weather parameters are not poised to change a lot during the hour. The points
were reduced to 69924 observations from 349622. Afterward, we built an ARIMA model for the prediction of daily weather parameters separately.
