# Diabetes Prediction Project

This project aims to predict diabetes outcomes using a **RandomForestClassifier** based on features like Age, Glucose, and BMI. The model was trained using a publicly available dataset and achieves an accuracy score of 78%.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model](#model)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction
Diabetes is a chronic condition that affects millions of people worldwide. Early prediction of diabetes can help in better management and care for individuals at risk. This project builds a machine learning model to predict whether a person is likely to develop diabetes based on their medical history and biometric data.

## Dataset
The dataset used for this project contains the following features:
- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body Mass Index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: A function that scores the likelihood of diabetes based on family history
- **Age**: Age of the individual

The target variable is whether the person has diabetes (1) or not (0).

## Model
We used a **RandomForestClassifier**, a robust machine learning algorithm known for its performance on classification tasks. Key steps included:
1. Data pre-processing (handling missing values, scaling features)
2. Model training using the dataset
3. Model evaluation using accuracy and other relevant metrics.

## Technologies Used
- **Python**
- **Pandas**: For data manipulation
- **Scikit-learn**: For building and evaluating the machine learning model
- **Matplotlib/Seaborn**: For data visualization

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sumanth-poojary/diabetes-prediction-project.git
   cd diabetes-prediction-project

## Result 
The accuracy score using RandomForestClassifier model was **78%** and **77%** using RandomSearchCV

## Conclusion
The model performs reasonably well for predicting diabetes outcomes but could be further improved by experimenting with other algorithms or tuning hyperparameters. Additional steps could involve using more features, handling imbalanced data, or exploring deep learning models.
