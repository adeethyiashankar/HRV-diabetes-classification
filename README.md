# HRV-diabetes-classification
Python code used to forecast CGM data 30, 60, and 90 minutes ahead and to classify HRV data as diabetes or healthy

Forecast:
* KRR
* ARIMA
* Prophet
* LSTM

Classification:
* Random Forest
* XGBoost
* Support Vector Machine (SVM)

Also contains the figures for each of the models
* ARIME p1-7 and all of the CSVs are in units mmol/L rather than mg/dL
* Convert by multiplying mmol/L values by 18.016
