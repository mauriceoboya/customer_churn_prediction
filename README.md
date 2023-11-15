# Customer Churn Predictive Model

Customer churn, the loss of customers over time, is a critical metric affecting business profitability. This predictive model aims to forecast customer churn based on historical data, enabling the implementation of targeted retention efforts.

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Data Visualization](#data-visualization)
- [Predictive Model](#predictive-model)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction

Customer churn is a common challenge faced by businesses. This predictive model uses historical data to forecast the likelihood of a customer churning, allowing businesses to take proactive measures to retain customers.

## Data

The dataset used in this model includes the following features:
- Age
- Total_Purchase
- Account_Manager
- Years
- Num_Sites
- Onboard_date
- Churn

## Data Visualization

Exploratory data analysis is performed to understand the distribution of customer ages and visualize customer churn.

## Predictive Model

A neural network model is implemented using TensorFlow and Keras. The model is trained on historical data and evaluated for accuracy.

## Usage

To use this predictive model, follow these steps:
1. Install the required dependencies.
2. Load the dataset.
3. Preprocess the data.
4. Train the model.
5. Evaluate the model.

## Results

The model achieves a certain level of accuracy and provides insights into precision, recall, and F1-score for both classes (churned and retained customers).

## License

This project is licensed under the [MIT License](LICENSE).

