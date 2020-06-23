# Feature-Engineering
Feature Engineering and Selection for a Time Series Forecasting. /n
We perform the processing of feature generation of a time series dataset and then select the most relevant features for prediction 
n/
We then further reduce the dimentionality of the features using Principal Component Analysis
The features are generating from the close price of a time series stock for a specified period
The following are the categories of features generated:
  Date Related Features
  Lag Features
  Rolling Window Features
  Expanding Window Features
  Technical Indicators
The feature selection is achieved by looking at the correlations of the features with the target variable as well as correlation among the features
We then employ XGBoost package to determine feature to return based on feature importance 

