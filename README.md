# Chennai_House_Price_Prediction

This repository contains the code and documentation for a machine learning model that predicts house prices in Chennai. The project involves data collection, data preprocessing, model building, and evaluation.

## Introduction

The goal of this project is to predict the prices of houses in Chennai based on various features such as location and size. Accurate house price predictions can help buyers, sellers, and real estate professionals make informed decisions.

## Data

The dataset used for this project includes various features that influence house prices in Chennai. The data is sourced from [Kaggle](https://www.kaggle.com/datasets/amaanafif/chennai-house-price).

Key features in the dataset:
- Location
- Size (in square feet)
- Number of bedrooms
- Number of bathrooms
- Age of the property

## Methodology

The project follows these steps:
1. Data Collection: Gathering the data from reliable sources.
2. Data Preprocessing: Cleaning and transforming the data to make it suitable for modeling.
3. Exploratory Data Analysis (EDA): Analyzing the data to uncover patterns and relationships.
4. Feature Engineering: Creating new features to improve model performance.
5. Model Building: Training various machine learning models to find the best predictor.
6. Model Evaluation: Assessing the performance of the models using appropriate metrics.

## Model

The model is built using Scikit-Learn. Several algorithms were tried and tested, including:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

The final model chosen is Linear Regression based on its performance metrics.

## Results

The performance of the final model is evaluated using:

- R-squared (R²) score : [0.8201136604661972] 
- An R² of 0.82 indicates that 82% of the variance in house prices is explained by the model. This is generally considered a strong result, indicating a good fit.
- Linear Regression was chosen as the final model due to its simplicity and strong performance, achieving a best score of 0.859782 and an R² score of 0.82, which indicates that it effectively explains 82% of the variance in Chennai house prices while maintaining interpretability and computational efficiency.

