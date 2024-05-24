# Bank Customer Retention Prediction using Artificial Neural Network (ANN)

## Overview

This project leverages an Artificial Neural Network (ANN) to predict whether a customer will stay with a bank or leave. By analyzing customer data, the model aims to provide actionable insights for improving customer retention strategies.

## Table of Contents

- [Project Description](#project-description)
- [Installation](#installation)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Results](#results)
- [Contact](#contact)


## Project Description

The primary goal of this project is to build an ANN model capable of predicting the likelihood of a bank customer churning. By training the model on historical customer data, it can identify patterns and factors that contribute to customer churn.

## Installation

Follow these steps to set up the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/vurali/Bank-Customer-Retention-Prediction-using-ANN.git
   cd Bank-Customer-Retention-Prediction-using-ANN

## Dataset

The dataset used in this project is a synthetic dataset representing bank customers. Below are the details of the dataset features:

- CustomerId: Unique identifier for each customer
- Surname: Customer's surname
- CreditScore: Credit score of the customer
- Geography: Customer's location (categorical feature with values like 'France', 'Spain', 'Germany')
- Gender: Gender of the customer (categorical feature with values 'Male' and 'Female')
- Age: Age of the customer
- Tenure: Number of years the customer has been with the bank
- Balance: Account balance
- NumOfProducts: Number of bank products the customer is using
- HasCrCard: Whether the customer has a credit card (1=Yes, 0=No)
- IsActiveMember: Whether the customer is an active member (1=Yes, 0=No)
- EstimatedSalary: Estimated annual salary of the customer
- Exited: Whether the customer has exited the bank (target variable, 1=Yes, 0=No)



## Data Preprocessing

Data preprocessing steps are crucial for preparing the data for the model. The steps include:

- Encoding categorical variables
  - One-hot encoding for categorical features
  - Label encoding for binary features
- Feature scaling
  - Standard scaling for continuous features
  - Normalization for highly skewed features
 

## Results

The model achieved the following performance metrics on the test set:

- Accuracy: 85%


## Contact
For any inquiries or feedback, please contact:

- Name: Murali Krishna
- Email: pulimurali07@gmail.com
