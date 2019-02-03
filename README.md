# Kaggle - House Prices: Advanced Regression Techniques

This analysis is part of an assignment for the SYS 6018 Data Mining Course and involved participating in the Kaggle competition (https://www.kaggle.com/c/house-prices-advanced-regression-techniques) . I did this analysis with 2 other students in class and we were graded a A+ (96/100) for our submission.

#### Objective 
The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset. 
This competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, the goal of this analysis is to predict the final price of each home.

## Description of files

## train.csv
* This is the given training file in the Kaggle competition

## test.csv
* This is the given test file in the Kaggle competition

## code.R
* It contains the data loading, cleaning (filling legit NAs), and imputation of missing data
* It also contains exploratory data analysis and removal of outliers
* To eliminate bias, we normalized all the variables
* We feature engineered the data as well as performed one - hot encoding to reduce bias by multi collinearity and categorical variables
* The statistical methods were selected based on Assignment guidelines
* Parametric modeling method for Sale Price Prediction using the House Price Dataset
* Non-Parametric modeling (user defined KNN) for Sale Price Prediction using the House Price Dataset

## non-param_soln.csv
* It contains the Sale Price Predictions for all the IDs in test.csv (using all variables as regressors) under the non-parametric method

## param_soln.csv
* It contains the Sale Price Predictions for all the IDs in test.csv (using all variables as regressors) under the parametric method

## OUTPUT

* Under both Parametric and Non-Parametric approaches, we got the best Kaggle Public Score when we used all the variables for modeling Sale Price
