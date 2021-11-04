# Wavelet Based Machine Learning Approaches Towards Precision Medicine in Diabetes Mellitus
Python code used to forecast CGM data 30, 60, and 90 minutes ahead, classify HRV data as diabetes or healthy, and subtype diabetes mellitus by demographic

Forecast:
* KRR
* ARIMA
* Prophet
* LSTM

Classification:
* Random Forest
* XGBoost
* Support Vector Machine (SVM)

Diabetes Subtyping:
* tSNE
* UMAP

Also contains the figures for each of the models
* ARIMA p1-7 and all of the CSVs are in units mmol/L rather than mg/dL
* Convert by multiplying mmol/L values by 18.016
