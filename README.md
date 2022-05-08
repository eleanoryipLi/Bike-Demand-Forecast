# Bike-Demand-Forecast

Objective: Predict the total number of Washington D.C. bicycle users on an hourly basis.

Outcome: built machine learning pipelines that automate the workflows of data cleaning, feature engineering, hyperparameter tuning, and model evaluation. Achieved R2 score of 0.8636 using the Extra Trees model.

Data:<br />
	- Training data: whole 2011 and first 3 quarters of 2012.<br />
	- Test data: 4th quarter of 2012.<br />
	- Target: total number of users (cnt)<br />
	- Error metric: R2 score <br />

Feature descriptions:<br />
	- instant: record index<br />
	- dteday : date<br />
	- hr : hour (0 to 23)<br />
	- weathersit : Weather situation<br />
	- temp : Normalized temperature in Celsius. The values are divided to 41 (max)<br />
	- atemp: Normalized feeling temperature in Celsius. The values are divided to 50 (max)<br />
	- hum: Normalized humidity. The values are divided to 100 (max)<br />
	- windspeed: Normalized wind speed. The values are divided to 67 (max)<br />
	- casual: count of casual users<br />
	- registered: count of registered users<br />
	- cnt: count of total rental bikes including both casual and registered
