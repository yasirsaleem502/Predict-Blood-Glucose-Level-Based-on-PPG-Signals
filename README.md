# Predict Blood Glucose Level Based on PPG Signals

![Titanic](https://img.shields.io/badge/dataset-Titanic-blue)
![Python](https://img.shields.io/badge/Python-3.8+-green)
![Jupyter Notebook](https://img.shields.io/badge/Tools-Jupyter%20Notebook-orange)
![Pandas](https://img.shields.io/badge/Library-Pandas-yellow)
![Seaborn](https://img.shields.io/badge/Library-Seaborn-lightblue)
![NumPy](https://img.shields.io/badge/Library-NumPy-lightblue)
![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-orange)


### Project Overview

This project aims to predict blood glucose levels using Photoplethysmogram (PPG) signals. By analyzing the PPG waveform, along with other physiological data, the model predicts glucose levels, providing a non-invasive solution for diabetes management. The project leverages machine learning models, including linear regression, decision trees, and neural networks, to deliver accurate predictions.

### Table of Contents

- [Introduction](#introduction)
- [Dataset Description](#dataset-description)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Building](#model-building)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)
- [Contact](#contact)



### Introduction

Blood glucose monitoring is a crucial aspect of managing diabetes, and traditional methods often require invasive procedures. This project focuses on predicting blood glucose levels using Photoplethysmogram (PPG) signals, which can be obtained from wearable devices. By using machine learning models, this project aims to provide an accurate and non-invasive alternative for glucose level monitoring.

### Dataset Description

The dataset used in this project contains the following features:

PPG Signal (mV): The raw PPG waveform values.

Heart Rate (bpm): The individual's heart rate in beats per minute.

Systolic Peak (mmHg): Maximum blood pressure during heart contraction.

Diastolic Peak (mmHg): Minimum blood pressure between heartbeats.

Pulse Area: The area under the pulse waveform.

Gender: Gender of the patient (1 for Male, 0 for Female).

Height (cm): The height of the individual.

Weight (kg): The weight of the individual.

Age Range: A categorical representation of the individual's age group.

The dataset includes demographic information and physiological features that are used to predict the blood glucose level.

dataset link : https://www.kaggle.com/datasets/muhammadyasirsaleem/ppg-signal-with-blood-sugar-level-data

### Data Preprocessing

Data preprocessing steps included:

Handling missing values.

Normalizing numerical features such as heart rate, height, and weight.

Encoding categorical variables (e.g., gender and age range).

Feature scaling to ensure that all input features are on a similar scale for model training.

### Exploratory Data Analysis

In this section, relationships between different features and glucose levels were analyzed. Visualizations and statistical methods were used to understand trends, correlations, and outliers in the dataset. This helped identify the most influential factors for predicting glucose levels.

### Model Building

Multiple machine learning models were used to predict blood glucose levels:

Linear Regression: To establish a baseline model for predicting glucose levels.

Decision Trees: To capture non-linear relationships between features.

Polynomial regression:is a type of regression analysis that models the relationship between the independent variable and the dependent variable as an nth-degree polynomial.

The models were trained using the preprocessed dataset, and hyperparameter tuning was performed to achieve the best possible accuracy.

### Model Evaluation

The model's performance was evaluated using various metrics:

Mean Absolute Error (MAE): Measures the average magnitude of errors in predictions.

Mean Squared Error (MSE): Indicates the average squared difference between predicted and actual values.

R-squared (R²): Evaluates the goodness of fit of the model.

These metrics helped assess the accuracy and reliability of each model.

### Conclusion

The predictive models developed in this project provide a promising solution for non-invasive glucose monitoring. The results show that machine learning models can effectively predict blood glucose levels from PPG signals. Future work includes improving model accuracy through deep learning techniques and deploying the solution in wearable devices for real-time monitoring.



### Contact

For any inquiries, questions, or collaboration opportunities, please reach out to:

Name: Arsalan Ashraf

Email: [your-email@example.com]

GitHub: https://github.com/username

