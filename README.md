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
- RainToday: Boolean: 1 if precipitation (mm) in the 24 hours to 9am exceeds 1mm, otherwise 0
- WindDir3pm: Direction of the wind at 3pm
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
- Humidity9am: Humidity (percent) at 9am
- Humidity3pm: Humidity (percent) at 3pm
- Pressure9am: Atmospheric pressure (hpa) reduced to mean sea level at 9am
- Pressure3pm: Atmospheric pressure (hpa) reduced to mean sea level at 3pm
- Cloud9am: Fraction of sky obscured by cloud at 9am. This is measured in "oktas", which are a unit of eigths. It records how many eigths of the sky are obscured by cloud. A 0 measure indicates completely clear sky whilst an 8 indicates that it is completely overcast.
- Cloud3pm: Fraction of sky obscured by cloud (in "oktas": eighths) at 3pm. See Cload9am for a description of the values
- Temp9am: Temperature (degrees C) at 9am
- Temp3pm: Temperature (degrees C) at 3pm

**Target Variable**
- RainTomorrow: The target variable. Did it rain tomorrow? (1=yes, 0=no)
***

## <a name="Results"></a> Result

On test set: 
- Random Forest Classifier: Accuracy = 0.85 and ROC = 0.82.
- Ada Boost Classifier: Accuracy = 0.84 and ROC = 0.79.
