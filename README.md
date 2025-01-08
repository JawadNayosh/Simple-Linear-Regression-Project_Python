# Simple-Linear-Regression-Project_Python
Simple Linear Regression Project

## Overview

This project demonstrates the application of a simple linear regression model to explore the relationship between a car's weight and its fuel efficiency (miles per gallon, mpg). The objective is to predict mpg based on a vehicle's weight and evaluate the model's performance using statistical metrics and visualizations.

##  Goals

Analyze the dataset to understand the relationship between car weight and mpg.

Train a simple linear regression model using the Ordinary Least Squares (OLS) method.

Evaluate the model using metrics like RMSE, MAE, and R-squared.

Visualize the results to validate model assumptions and interpretations.

## Programming Language: Python

## Libraries:

numpy, pandas: Data manipulation and analysis

matplotlib, seaborn: Data visualization

scikit-learn: Data splitting and metrics

statsmodels: Linear regression analysis


## Dataset

The dataset includes:

Weight: The weight of the car (predictor variable).

mpg: The fuel efficiency of the car in miles per gallon (target variable).

Implementation Steps

Data Preprocessing

Loaded the dataset.

Split data into training (70%) and testing (30%) sets.


## Model Training

Trained a simple linear regression model using the OLS method from statsmodels.

Model coefficients:

Intercept (const): 46.187

Weight coefficient: -0.0077

## Interpretation:

For every unit increase in weight, mpg decreases by approximately 0.0077 units, holding other factors constant.


# Model Evaluation

Evaluated the model on both training and testing datasets using:

## Root Mean Squared Error (RMSE):

Train: 4.49

Test: 3.95

## Mean Absolute Error (MAE):

Train: 3.40

Test: 3.03

## Mean Absolute Percentage Error (MAPE):

Train: 14.94%

Test: 13.03%

R-squared:

Train: 0.67

Test: 0.73


## Visualization

Created plots to validate the linear relationship and check residuals.

Visualizations confirmed the negative correlation between weight and mpg.


# Key Results

Adjusted R-squared:

0.67 on training data

0.73 on test data

The model predicts mpg within an average error of approximately 3 units on the test set.

MAPE of 13% suggests reasonable prediction accuracy.


# Observations

The training and testing metrics are comparable, indicating no overfitting or underfitting.

The model demonstrates a statistically significant relationship between car weight and mpg.

