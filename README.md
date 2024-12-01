# drug-classification-models
A collection of machine learning models for drug classification using K-Nearest Neighbors, Logistic Regression, Decision Trees, and Support Vector Machines. This project evaluates and compares the performance of these models on a drug classification dataset.

## Overview
This repository contains implementations of various machine learning models for drug classification. The models evaluated include K-Nearest Neighbors (KNN), Logistic Regression, Decision Trees, and Support Vector Machines (SVM). The primary goal is to determine which model performs best on the drug classification dataset based on accuracy, precision, recall, and F1-score.

## Dataset
The dataset used for this project is the `drug200.csv`, which contains information about patients and their respective drug classifications. The dataset includes features such as:
- Age
- Sex
- Blood Pressure (BP)
- Cholesterol levels
- Sodium levels
- Drug type (target variable)

## Models Implemented
1. **K-Nearest Neighbors (KNN)**
2. **Logistic Regression**
3. **Decision Trees**
4. **Support Vector Machines (SVM)**

## Performance Summary
The following table summarizes the performance metrics for each model:

| Model                | Accuracy | Precision | Recall | F1-score |
|----------------------|----------|-----------|--------|----------|
| K-Nearest Neighbors   | 0.850    | 0.875     | 0.850  | 0.851    |
| Logistic Regression   | 0.925    | 0.936     | 0.925  | 0.921    |
| Decision Trees        | 1.000    | 1.000     | 1.000  | 1.000    |
| Support Vector Machines| 0.975    | 0.977     | 0.975  | 0.974    |

### Best Model for Each Metric
- **Best Accuracy**: Decision Trees with an accuracy of 1.00
- **Best Precision**: Decision Trees with a precision of 1.00
- **Best Recall**: Decision Trees with a recall of 1.00
- **Best F1-score**: Decision Trees with an F1-score of 1.00

## Installation
To run the code, ensure you have Python installed along with the required libraries. You can install the necessary libraries using pip:

```bash
pip install pandas numpy scikit-learn matplotlib

License
This project is licensed under the MIT License 
