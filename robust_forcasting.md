# Robust Forecasting in Python and R

Risk Management System
Need to calculate the (actual, sever) cost

## Preprocessing

Ensure it is timeseries
Check for completeness (fill null values through imputation)
Remove leap days
Make sure data has at least one complete season
Truncate to seasons (Remove from the past)

### Outlier/Anamoly Detection

Do you need this if robust?
Outlier: abnormal distance
Anomaly: Illegitimate data point
Don't use 95% mass if there is a trend!

## Forecasting Models

Regression
	StatsModels
	XGBoost
	
ARIMA
	Forecast
	StatsModels
	Pyramid
	
Exponential Smoothing
	Forecast
	
Structural Models
	Bayesian Structural Time Series
	Pyflux
	Prophet

## Evaluation

Scale Dependent (MSE etc.)
why use MFE?

Scale independent (Mean Absolute Scaled Error)

## Optimization

TBATS AutoARIMA PyARIMA Prophet Pyflux
Different hyperparameters
Log, BoxCox, Default

(Looks like he isn't using robust statistics)
Why did he remove unnecessary metrics

## Scale + Cost Optimization

- Docker
- Used Celery to orchastrate


ECS

2.6 million forecasts (using spot instances)
