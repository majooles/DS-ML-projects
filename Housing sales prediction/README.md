# Project Overview

This project aims to develop a predictive model for housing prices using machine learning techniques. The dataset consists of various features related to residential properties. Key steps include data preprocessing, feature transformation, model training, and evaluation.

## Data Preprocessing

- Loading data from CSV files.
- Handling null values by dropping columns with over 80% missing values and imputing others.
- Feature encoding and creation of a new feature, 'HouseAge'.
- Standardization of numeric features.
- Splitting the dataset into training and testing sets.

## Target Transformation

- Applying a log transformation to the target variable, 'SalePrice', due to positive skewness.

## Model Training

- Using Ridge regression with regularization to prevent overfitting.
- Evaluating the model's performance using root mean squared error (RMSE) on the training set.

## Next Steps

- Further exploration of feature engineering techniques.
- Experimentation with different algorithms and hyperparameter tuning.
- Cross-validation and deployment of the final model for predicting housing prices.
