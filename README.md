# Fish Weight Prediction Using Linear Regression

This project aims to predict the weight of fish based on various physical measurements using a linear regression model.

# Dataset
The dataset includes the following features:
  Category: Numerical category identifier for the species.
  Species: Type of fish (e.g., Bream).
  Weight: Weight of the fish in grams.
  Height: Height of the fish in cm.
  Width: Width of the fish in cm.
  Length1: Length from the nose to the beginning of the tail in cm.
  Length2: Length from the nose to the notch of the tail in cm.
  Length3: Total length from nose to tail in cm.

Steps
Data Preprocessing:

Load the dataset and explore the data.
Handle any missing values and encode categorical features if necessary.
Feature Selection:

Identify relevant features for predicting fish weight.
Model Development:

Split the data into training and testing sets.
Train a linear regression model using the training set.
Model Evaluation:

Evaluate the model's performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.
Prediction:

Use the model to predict weights on new fish data.
