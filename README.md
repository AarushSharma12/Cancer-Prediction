# Breast Cancer Prediction using Logistic Regression

This project implements a logistic regression model to predict breast cancer using the Breast Cancer Wisconsin dataset. The model is evaluated with key performance metrics, achieving high predictive accuracy and reliability.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)

## Introduction
This repository provides a logistic regression model to predict whether a tumor is malignant or benign based on the characteristics of cell nuclei in breast cancer tissue samples. The model is trained on the Breast Cancer Wisconsin dataset and achieves an accuracy of **97%** on the test data.

## Dataset
The dataset used in this project is the Breast Cancer Wisconsin dataset. It contains 569 samples and 30 features representing various characteristics of cell nuclei in breast cancer tissue images. The target variable indicates whether the tumor is malignant (1) or benign (0).

## Installation
To run this project locally, you'll need Python 3 installed along with the following libraries:
- `numpy`
- `pandas`
- `scikit-learn`

You can install the required dependencies using pip.

## Data Preprocessing
The preprocessing steps include:
1. **Feature scaling:** Features are standardized using `StandardScaler` to normalize the data.
2. **Train-test split:** The dataset is split into training and test sets in a 70:30 ratio to ensure proper model evaluation.

## Model Training
The logistic regression model is created using `LogisticRegression()` from the `scikit-learn` library. The steps involved are:
1. Initialize the logistic regression model.
2. Train the model on the training data.
3. Use the trained model to predict the target variable for the test data.

## Evaluation
The model is evaluated based on the following key metrics:
- **Accuracy:** 97%
- **Precision:** 
  - Benign (0): 0.98
  - Malignant (1): 0.96
- **Recall:**
  - Benign (0): 0.97
  - Malignant (1): 0.97
- **F1-score:**
  - Benign (0): 0.98
  - Malignant (1): 0.96


## Conclusion
The logistic regression model effectively predicts breast cancer with high accuracy and strong precision-recall metrics. The model shows excellent performance in distinguishing between malignant and benign cases. Potential improvements could involve testing additional models or fine-tuning hyperparameters.
