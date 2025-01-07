# CODTECH_Task-2_Sanskruti

Name: Sanskruti Thakur

Company: CODTECH IT SOLUTIONS

ID: CT08DS193

Domain: Data Science

Duration: December 2024 to January 2025

# Overview of the Project

Project: Linear Regression on the California Housing Dataset

This project demonstrates the use of linear regression for predicting house prices using the California Housing dataset. The dataset contains information about various features of California districts and their corresponding median house values, making it ideal for regression modeling and evaluation.

Key Objectives:

Data Loading and Preparation:

a) Use scikit-learn to fetch the California Housing dataset.

b) Separate the dataset into features (predictors) and the target variable (house prices).

c) Split the data into training and testing sets to evaluate model performance on unseen data.

Model Development and Training:
Implement a linear regression model using scikit-learn. Train the model on the training set to learn the relationship between features and house prices.

Model Evaluation:
Evaluate the model's predictive performance on the test set using key metrics:

a) Mean Squared Error (MSE): Measures the average squared difference between predicted and actual values.

b) Mean Absolute Error (MAE): Measures the average magnitude of prediction errors.

c) R-squared (R²): Indicates the proportion of variance in the target variable explained by the model. Compute accuracy as a percentage of the variance explained by the model (R² * 100).

Visualization of Results:
Create a scatter plot comparing actual vs. predicted house values. Overlay a red line representing perfect predictions (where actual equals predicted) to assess the model’s alignment with the ideal scenario.

Tools and Libraries Used:

a) scikit-learn:

fetch_california_housing: Provides the dataset.

train_test_split: Splits the data into training and testing subsets.

LinearRegression: Implements the regression model.

Metrics: mean_squared_error, mean_absolute_error, and r2_score for performance evaluation.

b) matplotlib: For data visualization.

c) numpy: For efficient numerical computations.

Project Flow:

a) Load and inspect the California Housing dataset.

b) Split the data into training and testing subsets.

c) Build and train a linear regression model using the training data.

d) Evaluate the model on test data using multiple performance metrics.

e) Visualize the actual vs. predicted values to identify patterns and potential errors.

Insights and Applications:
The evaluation metrics and visualizations provide insights into how well the linear regression model predicts house prices. The project highlights the strengths and limitations of linear regression, offering opportunities to explore more advanced models (e.g., polynomial regression, decision trees) for better predictions. Suitable for beginners learning regression techniques and applying them to real-world datasets.

Intended Use:
This project is a practical introduction to:

a) Regression modeling in Python.

b) Understanding and interpreting evaluation metrics.

c) Visualizing model predictions to assess performance.
Preparing for more advanced machine learning tasks.
