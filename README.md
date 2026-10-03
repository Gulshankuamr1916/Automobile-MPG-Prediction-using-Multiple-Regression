# Automobile-MPG-Prediction-using-Multiple-Regression
This project uses the UCI Auto MPG Dataset to predict a car’s fuel efficiency (measured in Miles Per Gallon – MPG) based on its specifications.
The project compares Multiple Linear Regression, Ridge Regression, and Lasso Regression models.

📌 Project Overview
Dataset: Auto MPG Data (UCI Machine Learning Repository)

The target variable is mpg (fuel efficiency).

Additional engineered features:

power_to_weight = horsepower ÷ weight

car_age = 2025 – model_year

# Models used:

Multiple Linear Regression (MLR)

Ridge Regression

Lasso Regression

# Steps in the Code

Import Libraries → pandas, scikit-learn

Load Dataset → UCI Auto MPG dataset

Data Cleaning → Removed missing values

Feature Engineering → Created power_to_weight and car_age

Define Features and Target

Train-Test Split (80% training, 20% testing)

Feature Scaling with StandardScaler

# Train Models

 Multiple Linear Regression

 Ridge Regression

 Lasso Regression

# Model Evaluation

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

Feature Importance → Print regression coefficients

Prediction for New Car → Model predicts MPG for unseen car specifications
