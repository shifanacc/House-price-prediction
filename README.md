# House Price Prediction using Regression

## Introduction

This project focuses on predicting house prices using machine learning regression techniques. The dataset contains various house features such as area, number of bedrooms, bathrooms, and location details. The goal is to analyze these features and build a model that can accurately predict house prices.
The project applies multiple regression algorithms including Linear Regression, Decision Tree Regressor, and Random Forest Regressor to compare their performance and identify the best model.

## Dataset

- Source: Kaggle (House Price Prediction Dataset)
- Features: 20 input features
- Target: Price (house selling price)
- Each row represents a house with its characteristics

## Data Preprocessing

- Checked for missing values (none found)
- Checked for duplicate values (none found)
- Removed unnecessary columns like `id` and `date`
- Handled outliers in price
- Scaled features for better model performance

## Exploratory Data Analysis (EDA)

- Histogram: Used to understand data distribution
- Scatter Plot: Showed relationship between area and price
- Boxplot: Detected outliers in price
- Heatmap: Showed correlation between features

## Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Each model was trained and tested to compare performance.

## Model Evaluation

Models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

Random Forest performed the best among all models due to its ability to handle complex relationships and reduce overfitting.

## Conclusion

In this project, machine learning techniques were successfully applied to predict house prices. After comparing all models, Random Forest Regressor gave the best performance. This project demonstrates how regression algorithms can be used for real-world prediction problems.

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Explanation Video

A detailed explanation video is provided below. Please refer to it to understand the project workflow and results
