# Time-Series-Data-Analysis-For-Air-Quality-using-Auto-Regressive-Model and Mongo database
Dar es Salaam Air Quality Analysis and Time Series Modeling
by Sileshi N
This repository contains data collection, cleaning and analyses of air quality data of Dar es Salaam in 2018. We used the data from twelve sites located in around Beijing's city center.

The data set was provided by the authors of 'Cautionary Tales on Air-Quality Improvement' ), a paper published in Proceedings of the Royal Society.

Project
For this project, we aim to analyze the sampled particulate matter from the twelve testing sites in Beijing in order to identify key trends and predict the levels of PM 2.5 (particulate matter with a circumference of 2.5 microns).

This is small particulate matter that can be suspended in the air for long periods of time before it enters the lungs.

First, we moved to combine all of the twelve sites into a single dataset interpolating the data.

We tested for stationarity and whether there was correlation between the features and time periods throughout our dataset.

Next, we began to fit models in an effort to prepare our models to predict the last twenty percent of the data that we had set aside as a test case.

Due to the time constraints and large amount of data, we decided to focus on a univariate time series forecast vs a multivariate time series forecast. One reason for the switch was that our hardware was unable to keep up with the amount of observations and features in an hourly prediction with multiple feature.


To whom does it matter if we can predict the amount of particulate matter in the air?
Residents of an Area and Tourists:
Will they be able to enjoy time outdoors?
People Who Suffer From Respiratory Illnesses:
Will their conditions worsen? Do they have to worry about loved ones contracting the same illness if not already predisposed? Will this contribute to premature death?
Understanding how different countries and regions may battle against the proliferation of particulate matter

Are some regions experiencing a rise in PM 2.5 while others are experiencing a decrese?
Understanding the viability in different models

Is it better to use a Facebook Prophet or a basic ARIMA?
Will SARIMAX models work with this data set?
Does the best model do a good job of predicting the target levels?
