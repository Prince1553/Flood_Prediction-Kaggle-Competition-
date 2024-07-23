# Flood_Prediction-Kaggle-Competition-
For the train and test data,visit the link :
https://www.kaggle.com/competitions/playground-series-s4e5/data
 

# Flood Prediction Using Regression Models

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project aims to predict flood levels using various regression models.The goal of this competition is to predict the probability of a region flooding based on various factors.



## Dataset
The dataset used for this project includes various hydrological and meteorological features that influence flood levels. The key columns in the dataset are:

- `Date`: Date of the observation
- `Rainfall`: Amount of rainfall (in mm)
- `Temperature`: Average temperature (in °C)
- `Humidity`: Average humidity (in %)
- `RiverFlow`: River flow rate (in cubic meters per second)
- `FloodLevel`: Flood level (target variable, in meters)
and so on......

## Feature Engineering
Feature engineering techniques applied in this project include:

- Handling missing values
- Encoding categorical variables (if any)
- Creating new features based on domain knowledge
- Scaling numerical features

## Modeling
Various regression models have been experimented with, including:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor
- LightGBM Regressor
- CatBoost Regressor

Hyperparameter tuning has been performed using techniques such as Grid Search and Random Search to optimize model performance.

## Evaluation
The models are evaluated using metrics such as:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

## Results
Ranked in top 30%, Achieved a RMSE of 3210 on the test set.

 
