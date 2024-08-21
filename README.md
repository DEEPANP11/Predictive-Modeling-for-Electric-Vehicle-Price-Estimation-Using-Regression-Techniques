# Predictive-Modeling-for-Electric-Vehicle-Price-Estimation-Using-Regression-Techniques
Electric Car Price Prediction
This project focused on predicting electric car prices using regression models. The dataset includes features related to car specifications and performance, which are used to train and evaluate different machine learning models.

Table of Contents
Project Overview
Dataset
Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Model Development
Results

The goal of this project is to build and evaluate various regression models to predict the prices of electric cars based on features such as acceleration, top speed, range, efficiency, and other characteristics.

Dataset
The dataset used in this project is ElectricCarData_Clean.csv, which includes the following features:

Brand: The manufacturer of the car.
Model: The model name of the car.
AccelSec: Acceleration time in seconds.
TopSpeed_KmH: Top speed in km/h.
Range_Km: Range of the car on a full charge in km.
Efficiency_WhKm: Efficiency in watt-hours per km.
FastCharge_KmH: Fast charging speed in km/h.
RapidCharge: Indicates if the car supports rapid charging (Yes/No).
PowerTrain: Type of powertrain (AWD/RWD).
PlugType: Type of plug used for charging.
BodyStyle: The body style of the car (e.g., Sedan, Hatchback).
Segment: The market segment of the car.
Seats: Number of seats in the car.
PriceEuro: Price of the car in euros.

Preprocessing
Data Cleaning: Removed unnecessary columns and handled missing values.
Outlier Detection and Removal: Identified and removed outliers from numerical features.
Feature Scaling: Standardized numerical features to improve model performance.
Encoding Categorical Features: Converted categorical features into dummy variables.

Exploratory Data Analysis (EDA)
Distribution Plots: Plotted histograms and KDE plots to understand the distribution of features like PriceEuro, Range_Km, Efficiency_WhKm, and TopSpeed_KmH.
Correlation Analysis: Analyzed correlations between features and the target variable to understand relationships.
Feature Importance: Used ExtraTreesRegressor to identify the most important features for predicting car prices.

Feature Engineering
Log Transformation: Applied log transformation to the PriceEuro to stabilize variance and make the relationship between features and target variable more linear.
Dummy Variables: Created dummy variables for categorical features to include them in the regression models.

Model Development
Linear Regression: Built and evaluated a linear regression model.
Random Forest Regressor: Built and evaluated a random forest regressor.
Gradient Boosting Regressor: Built and evaluated a gradient boosting regressor.
Results
Linear Regression:
R-squared: -100.62
RMSE: 3.72

Random Forest Regressor:
R-squared: 0.83
RMSE: 0.15

Gradient Boosting Regressor:
R-squared: 0.84
RMSE: 0.15
MAE: 0.12
MSE: 0.02
The Gradient Boosting Regressor provided the best performance in terms of R-squared and RMSE.

<img src="D:\photos\college pht\IMG-20220802-WA0001.jpg">

