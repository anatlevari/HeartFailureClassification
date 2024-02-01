# Heart Failure EDA and Prediction Project

## Introduction

This project is an introduction to data science, focusing on leveraging pandas for exploratory data analysis (EDA) and applying various machine learning algorithms for classification. The goal is to predict heart failure from a dataset containing 918 samples, each described by 11 features such as age, sex, and maximal heart rate. The dataset was taken from [here](https://www.kaggle.com/fedesoriano/heart-failure-prediction).


## Project Overview

The project is structured into two distinct parts, each contained in a separate file:

1. **Exploratory Data Analysis (EDA):** This phase involves deep data exploration to uncover insights, identify outliers, and perform visualizations. The findings from this phase are crucial in setting the stage for accurately classifying heart failure cases.
2. **Classification Using Machine Learning Algorithms:** In this phase, five classification algorithms are employed to predict heart failure, emphasizing recall and accuracy metrics. The primary objective is to reduce the number of false negatives to ensure effective prediction.

## Skills and Tools Used

- **Pandas:** Used extensively for data manipulation and analysis during the EDA phase. Tasks included checking and cleaning the data, identifying outliers, and visualizing data trends.
- **Machine Learning Algorithms:** Logistic Regression, K-Nearest Neighbors, Support Vector Machine, Decision Tree, and Random Forest were used for classification.

## EDA and Classification Process

### EDA File:
A comprehensive analysis of the dataset was conducted in the EDA file. This involved:
- Identifying and handling outliers.
- Visualizing data distributions and relationships among features.
- Preparing the data for the classification task, informed by insights gained from visualizations and outlier analysis.

### Classification File:
The classification file focuses on applying and comparing different machine-learning algorithms. Key points include:
- The Naive Bayes algorithm was excluded due to feature correlation, as identified in the EDA phase.
- Evaluation of each algorithm's performance, prioritizing recall to minimize false negatives in predictions.

## Conclusion
The maximal accuracy was achieved by a support vector machine classifier and is equal to 91%. In addition, I used the decision tree classification model for describing the most significant features that predict heart failure.



