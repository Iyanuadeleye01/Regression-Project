# Regression-Project
This is a time series forecasting project aimed to predict the store sales on  data from Corporation Favorita, a large Ecudorian-based grocery retailer.

DATA SOURCES
Th datasets for this project were sourced from 3 different domains:
i. Azubi Africa Database
ii. Google drive and 
iii. Github
The datasets are in 7 categories namely;
Train
Oil
Sample_submission
Test
Store
Transaction and
Holiday dataset.

The Train dataset has different features and the target variable and it was used to train different models in this project to select the model with the best performance.
The Oil dataset has the date and corresponding oil prices, this dataset was analyzed in this project to understand the effect of oil slump and surge on the store sales. Ecuador is considered to be an oil-rich country which have its economic base as the revenue received from the oil sector of the economy.
The Sample_submission dataset has the target variable and ID feature, this dataset was not considered for any analysis in this project because it is not significant to the project objective(s).
Test dataset is for testing the best performing model to forecast the next 15 day sales for the Favorita Store from the date where data collection stopped on the Train dataset.
Store dataset has information about the locations and distribution of Favorita Store types across the country.
Transaction dataset has features about the corresponding transactions on different stores sales.
Holiday dataset has features about the different holiday types with their corresponding dates, in this project the holiday types were analyzed to identify the possible influence they have on the store sales on different days there are observed both locally and nationally in Ecuador.
The Earthquate hit of mid April 2016 in Ecuador was a major natural event that could negatively impart store sales in that period, so much attention was given to that month in this project to assess how it influenced store sales across the country.

The Train dataset used to train models in this project is not stationary so it was differenced and made stationary after testing it again using KPSS method.
6 models were trained in this project;
1. Claasical models.
i. Auto Regressive (AR)
ii. Moving Average(MA)
iii. Auto Regressive Integrated Moving Average(ARIMA)
iv. Seasonal Auto Regressive Integrated Moving Average(SARIMA)
v. Seasonal Auto Regressive Integrated Moving Average(SARIMAX) X is the esogenous/external variable.
2. Supervised machine learning model.
XGBOOST Model


