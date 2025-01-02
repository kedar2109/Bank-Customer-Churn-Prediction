# Artificial Neural Network for Bank Customer Churn Prediction

## Project Overview

This project involves training an Artificial Neural Network (ANN) model using a bank dataset to predict which customers are likely to leave the bank. The model helps the bank to proactively engage with customers who are at risk of churning.

## Dataset

The dataset contains various features related to bank customers, including:
- Row Number
- Customer ID
- Surname
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Exited (Target variable: 1 if the customer left, 0 otherwise)

## Model Architecture

The ANN model consists of the following layers:
1. Input Layer: Accepts the input features from the dataset.
2. Hidden Layers: Includes multiple fully connected layers with ReLU activation.
3. Output Layer: A single neuron with sigmoid activation to predict the probability of churn.


