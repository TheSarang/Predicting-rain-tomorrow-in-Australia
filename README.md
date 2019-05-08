# Predicting-rain-tomorrow-in-Australia

## Table of Contents:
+ [Data Set](#Data_Set) </br>
+ [Result](#Results) </br>

## <a name="Data_Set"></a> Data Set 

This dataset contains daily weather observations from numerous Australian weather stations. Observations were drawn from numerous weather stations. The daily observations are available from http://www.bom.gov.au/climate/data. Copyright Commonwealth of Australia 2010, Bureau of Meteorology.

There are 23 features:

**Categorical Features**
- Date: The date of observation
- Location: The common name of the location of the weather station
- RainToday:
- RainTomorrow:
- WindDir3pm: Direction of the wind at 3am
- WindDir9am: Direction of the wind at 9am
- WindGustDir: The direction of the strongest wind gust in the 24 hours to midnight

**Numerical Features**
- MinTemp: The minimum temperature in degrees celsius
- MaxTemp: The maximum temperature in degrees celsius
- Rainfall: The amount of rainfall recorded for the day in mm
- Evaporation: The so-called Class A pan evaporation (mm) in the 24 hours to 9am
- Sunshine: The number of hours of bright sunshine in the day.
- WindGustSpeed: The speed (km/h) of the strongest wind gust in the 24 hours to midnight
- WindSpeed9am: Wind speed (km/hr) averaged over 10 minutes prior to 9am
- WindSpeed3pm: Wind speed (km/hr) averaged over 10 minutes prior to 3am
- Humidity9am:
- Humidity3pm:
- Pressure9am:
- Pressure3pm:
- Cloud9am:
- Cloud3pm:
- Temp9am:
- Temp3pm:

**Target Variable**
- default.payment.next.month: Default payment (1=yes, 0=no)
***

## <a name="Results"></a> Result

On test set: Recall = 0.73 and ROC = 0.78.

