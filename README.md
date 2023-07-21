# Automobile Price Prediction

This project aims to predict automobile prices based on various features using linear regression. The dataset used in this project is provided in CSV format and contains information about automobiles and their corresponding prices.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Data Preprocessing](#data-preprocessing)
  - [Handling Missing Values](#handling-missing-values)
- [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Correlation Analysis](#correlation-analysis)
- [Model Building](#model-building)
  - [Using Engine-Size as Independent Variable](#using-engine-size-as-independent-variable)
  - [Using Horsepower as Independent Variable](#using-horsepower-as-independent-variable)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)

## Introduction
This project utilizes the Python programming language and popular libraries such as Pandas, NumPy, and Scikit-learn to perform automobile price prediction using linear regression. The dataset is loaded, and missing values are handled to ensure clean and meaningful data for analysis. Then, two different linear regression models are built, one using 'engine-size' and the other using 'horsepower' as independent variables. The performance of each model is evaluated using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) metrics.

## Installation
To run the code and reproduce the results, make sure you have the following libraries installed in your Python environment:

- Pandas
- NumPy
- Scikit-learn

## Data Preprocessing
### Handling Missing Values
The original dataset contains missing values represented as '?'. In 'Solution 1', these missing values are replaced with 'NaN' (Not a Number). Then, missing values in numerical columns are filled with their respective median values, while missing values in categorical columns are filled with their respective mode values.

## Exploratory Data Analysis
### Correlation Analysis
In 'Solution 3', the correlation matrix of the cleaned dataset is calculated, and the features are ranked based on their correlation with the 'Price' column. This helps identify features strongly correlated with the target variable.

## Model Building
### Using Engine-Size as Independent Variable
'Solution 4' demonstrates building a linear regression model using 'engine-size' as the independent variable to predict 'price'. The dataset is split into training and testing sets, the model is trained, predictions are made, and the model's performance is evaluated.

### Using Horsepower as Independent Variable
'Solution 5' follows a similar approach as in 'Solution 4' but uses 'horsepower' as the independent variable to predict 'price'.

## Evaluation
For both models, evaluation metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) are printed to assess the accuracy and goodness of fit of each model.

## Conclusion
The README.md file provides an overview of the project, including its purpose, data preprocessing steps, exploratory data analysis, model building, and evaluation. It serves as a guide for anyone interested in understanding the code and replicating the automobile price prediction process using linear regression.
