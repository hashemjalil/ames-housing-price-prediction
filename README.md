# Ames Housing Price Prediction
## Overview
This project is about predicting house prices using the Ames Housing dataset. The goal was to understand what factors affect house prices and build models that can estimate them based on those features.

## What I did
I started by exploring the dataset to get a better understanding of the variables and how they relate to sale price. I looked at summary statistics and created a few graphs to visualize the data.

After that, I cleaned the dataset by removing columns with too many missing values and filling the remaining missing data using the median.

Then I built two models:
- A linear regression model as a baseline
- A random forest model to improve performance

## Results
The random forest model performed better than linear regression, with a lower error and a higher R-squared value. This shows that more flexible models can better capture patterns in the data.

## Files in this repository
- Initial_Results.ipynb → Contains all the code, analysis, and results
- README.md → Overview of the project

## Dataset
The dataset used is the Ames Housing dataset:
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data

## Notes
This is the initial stage of the project. Future improvements could include more feature engineering and tuning the models.
