# Wavelet Based Machine Learning Approaches Toward Precision Medicine in Diabetes Mellitus
Python code used to forecast CGM data 30, 60, and 90 minutes ahead, classify HRV data as diabetes or healthy, and subtype diabetes mellitus by demographic

Forecast:
* KRR
* ARIMA
* Prophet
* LSTM
![KRR CGM Forecast](https://github.com/adeethyiashankar/Wavelet-Based-Machine-Learning-Approaches-Toward-Precision-Medicine-in-Diabetes-Mellitus/blob/353c4c98775eeaf5bd324d235c7e7499c89d5545/Figures/KRR%20CGM%20Forecast%20on%20Patient%203.png)

Classification:
* Random Forest
* XGBoost
* Support Vector Machine (SVM)
![Random Forest HRV Classification Results](https://github.com/adeethyiashankar/Wavelet-Based-Machine-Learning-Approaches-Toward-Precision-Medicine-in-Diabetes-Mellitus/blob/353c4c98775eeaf5bd324d235c7e7499c89d5545/Figures/Random%20Forest%20HRV%20Diagnosis%20Confusion%20Matrices.png)

Diabetes Subtyping:
* tSNE
* UMAP

Also contains the figures for each of the models
* ARIMA p1-7 and all of the CSVs are in units mmol/L rather than mg/dL (convert by multiplying mmol/L values by 18.016)
