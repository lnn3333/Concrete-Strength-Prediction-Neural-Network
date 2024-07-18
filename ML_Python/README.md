# Classification Algorithm Practice Notebook

## Table of content
- Introduction
* Method and Metrics
- About The Dataset
* Credits

## Introduction
In this notebook, use the classification algorithms to classify the RainTommorow from the weather dataset.

## Method and Metrics
### Classification algorithms to create models
- Linear Regression
* K-Nearest Neighbors (KNN)
- Decision Trees
* Logistic Regression
- Support Vector Machines (SVM)

### Evaluation Methods
- Accuracy Score
* Jaccard Index
- F1-Score
* LogLoss
- Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
- R2-Score

### Content for each model
1. Define train and evalation dataset
2. Train the data
3. Predict the data
4. Evaluate the data
5. Create final report for comparision the data

## About The Dataset
The original source of the data is the Australian Government's Bureau of Meteorology. The latest data can be gathered from Bureau of Meteorology.

### Variable information
**Predictor Variables**
Date: The date of observation
Location: The name of the location of the observation
MinTemp: The minimum temperature in degrees Celsius
MaxTemp: The maximum temperature in degrees Celsius
Rainfall: The amount of rainfall recorded for the day in mm
Evaporation: The so-called Class A pan evaporation (mm) in the 24 hours to 9 am
Sunshine: The number of hours of bright sunshine in the day
WindGustDir: The direction of the strongest wind gust in the 24 hours to midnight
WindGustSpeed: The speed (km/h) of the strongest wind gust in the 24 hours to midnight
WindDir9am: The direction of the wind at 9 am
WindDir3pm: The direction of the wind at 3 pm
WindSpeed9am: The speed (km/h) of the wind at 9 am
WindSpeed3pm: The speed (km/h) of the wind at 3 pm
Humidity9am: The relative humidity (percent) at 9 am
Humidity3pm: The relative humidity (percent) at 3 pm
Pressure9am: The atmospheric pressure (hPa) at 9 am
Pressure3pm: The atmospheric pressure (hPa) at 3 pm
Cloud9am: The fraction of sky obscured by cloud at 9 am
Cloud3pm: The fraction of sky obscured by cloud at 3 pm
Temp9am: The temperature (degrees Celsius) at 9 am
Temp3pm: The temperature (degrees Celsius) at 3 pm
RainToday: Boolean: 1 if precipitation (mm) in the 24 hours to 9 am exceeds 1 mm, otherwise 0

**Target Variable**: 
- RainTomorrow
* Boolean: 1 if precipitation (mm) in the 24 hours to 9 am exceeds 1 mm, otherwise 0

## Credits
This project is part of the project of IBM Machine Learning with Python