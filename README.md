## Overview
This repository contains the implementation of a Multiple Linear Regression model to predict car prices based on various features such as mileage, engine size, fuel type, and more. The primary goal of this task is to develop a model that effectively estimates the prices of cars using the provided dataset.

## Model Description
The model utilizes the Multiple Linear Regression approach, which predicts a target variable (in this case, car prices) based on multiple independent variables. The following steps were involved in the development of the model:
### 1. Data Preprocessing
* Loaded the training and testing datasets.
* Handled missing values and categorical features through one-hot encoding.
* Normalized the numerical features for better model performance.
### 2. Model Training:
* Implemented gradient descent for training the model.
* Monitored the cost function to ensure the model converged.
### 3. Prediction:
* Used the trained model to make predictions on the test dataset.
* Evaluated the model's performance using metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.

## Visualization
Initially, interactive graphs were created using the `Altair` library to visualize the cost function and the actual vs. predicted prices. However, it was observed that the Altair graphs did not render correctly when uploaded to GitHub. As a result, the visualizations were switched to Seaborn, which provides static images that are compatible with GitHub.

## Conclusion
This project demonstrates the process of building and evaluating a Multiple Linear Regression model for predicting car prices. The transition from Altair to Seaborn for visualizations ensured better compatibility for sharing results on GitHub. The final model is assessed using key metrics to validate its performance.
