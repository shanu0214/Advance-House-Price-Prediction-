# Advance-House-Price-Prediction-
This repository builds a house price prediction model using the Boston Housing dataset. It loads and explores the data, prepares features and target, splits into training and test sets, trains a regression model, makes predictions, and evaluates performance using Mean Absolute Percentage Error (MAPE) for accuracy.
This repository implements a house price prediction model using the Boston Housing dataset. It walks through the typical machine learning workflow: loading data, exploring it, preprocessing, training a model, and evaluating performance.

Description

Data Loading – Imports the Boston dataset directly from a GitHub CSV file.

Exploratory Data Analysis (EDA) – Uses methods like .head(), .describe(), .info() to understand the dataset and check for missing values.

Data Preparation – Separates the target variable MEDV (median value of owner-occupied homes) from features.

Model Training – Splits the dataset into training and testing sets, trains a machine learning model (likely a regression model) to predict MEDV.

Prediction – Uses the trained model to predict house prices on the test set.

Evaluation – Calculates model performance using Mean Absolute Percentage Error (MAPE) to assess prediction accuracy.

The workflow is structured and follows a clean step-by-step approach from raw data to model evaluation.
