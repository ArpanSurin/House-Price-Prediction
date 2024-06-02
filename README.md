# HOUSE PRICE PREDICTION
## Overview
Develop a machine learning model for
predicting house prices using Python,
scikit-learn, and TensorFlow.

+ This project is a part of my machine learning virtual internship at **Bharat Intern**

## Problem Objective
The project aims at building a model of housing prices to predict median house values in California using the provided dataset. This model should learn from the data and be able to predict the median housing price in any district, given all the other metrics.

Districts or block groups are the smallest geographical units for which the US Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people). There are 20,640 districts in the project dataset.

## Dataset Information

| Column        |  Description                       |
| :-------------|  :-------------------------------- |
| **Longitude** (signed numeric - float)        |  Longitude value for the block in California, USA|
| **Latitude**  (numeric - float)    |  Latitude value for the block in California, USA |
| **Housing_median_age** (numeric - int)    |  Median age of the house in the block |
| **Total_rooms** (numeric - int)|  Count of the total number of rooms (excluding bedrooms) in all houses in the block |
| **Total_bedrooms** (numeric - float)|  Count of the total number of bedrooms in all houses in the block |
| **Population** (numeric - int)|  Count of the total number of population in the block |
| **Households** (numeric - int)|  Count of the total number of households in the block |
| **Median_income** (numeric - float)|  Median of the total household income of all the houses in the block |
| **Ocean_proximity** (numeric - categorical)| Type of the landscape of the block [ Unique Values : 'NEAR BAY', '<1H OCEAN', 'INLAND', 'NEAR OCEAN', 'ISLAND' ] |
| **Median_house_value** (numeric - int)| Median of the household prices of all the houses in the block |

[Dataset Link](https://www.kaggle.com/datasets/shibumohapatra/house-price)

## Algorithms
+ Random Forest Regressor
+ Linear Regression

**Best model Accuracy :** 82.44

![Model Screenshot](https://drive.google.com/uc?id=16DdR82xJIP456xipQbMnY2HaEPLEUEko)
