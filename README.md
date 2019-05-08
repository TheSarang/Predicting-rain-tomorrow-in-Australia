# Predicting-rain-tomorrow-in-Australia

## Table of Contents:
+ [Data Set](#Data_Set) </br>
+ [Result](#Results) </br>

## <a name="Data_Set"></a> Data Set 

This dataset contains daily weather observations from numerous Australian weather stations. Observations were drawn from numerous weather stations. The daily observations are available from http://www.bom.gov.au/climate/data. Copyright Commonwealth of Australia 2010, Bureau of Meteorology.

There are 23 features:

**Categorical Features**
- Date:
- Location:
- RainToday:
- RainTomorrow:
- WindDir3pm:
- WindDir9am:
- WindGustDir:

**Numerical Features**
- MinTemp:
- MaxTemp:
- Rainfall:
- Evaporation:
- Sunshine:
- WindGustSpeed:
- WindSpeed9am:
- WindSpeed3pm:
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

