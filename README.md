# Prophet Time Series Analysis and Forecasting Of Crime Rate in Chicago
	
The objective of this project is to predict the crime rate in Chicago using a historical dataset.

The Chicago Crime dataset contains a summary of the reported crimes that occurred in the City of Chicago from 2005 to 2017. Dataset has been obtained from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system.

(Data Source: https://www.kaggle.com/currie32/crimes-in-chicago)

Using the dataset I have tried to answer the following questions using Facebooks Prophet Time Series Analysis-

(1) What is the monthly future prediction of the crime rate in Chicago? (Ipython notebook)

(2) During which months does crime activity go up during the year? (Ipython notebook)

# Screenshots from the project:

![Predicting the future with FB Prophet](https://github.com/ahmedhumayun/Prophet-Time-Series-Analysis-and-Forecasting-Of-Crime-Rate-in-Chicago/blob/master/Future%20prediction.png "Predicting the future with FB Prophet")

![Interesting insights from FB Prophet](https://github.com/ahmedhumayun/Prophet-Time-Series-Analysis-and-Forecasting-Of-Crime-Rate-in-Chicago/blob/master/monthly%20and%20yearly%20trends.png "Interesting insights from FB Prophet")

# Facebook Prophet

Prophet is open source software released by Facebook’s Core Data Science team.
Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects.
At it’s core, Prophet is an additive model with the following components:
		y(t) = g(t) + s(t) + h(t) + ϵₜ
g(t) models trend, which describes long-term increase or decrease in the data. Prophet incorporates two trend models, a saturating growth model and a piecewise linear model, depending on the type of forecasting problem.
s(t) models seasonality with Fourier series, which describes how data is affected by seasonal factors such as the time of the year (e.g. more searches for eggnog during the winter holidays)
h(t) models the effects of holidays or large events that impact business time series (e.g. new product launch, Black Friday, Superbowl, etc.)
ϵₜ represents an irreducible error term
Prophet works best with time series that have strong seasonal effects and several seasons of historical data.
For more information, please check this out: https://research.fb.com/prophet-forecasting-at-scale/ https://facebook.github.io/prophet/docs/quick_start.html#python-api






