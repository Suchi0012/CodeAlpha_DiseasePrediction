# Disease Prediction from Medical Data

## Overview
This project focuses on predicting the possibility of heart disease using machine learning classification algorithms based on patient medical data.

## Objective
The objective is to build a machine learning model that can classify whether a patient is likely to have heart disease using clinical features.

## Dataset
Dataset Used:
- Heart Disease Dataset (UCI Machine Learning Repository)

The dataset contains patient information including:
- Age
- Sex
- Chest pain type
- Blood pressure
- Cholesterol
- Heart rate
- ECG-related features
- Other medical indicators

## Machine Learning Algorithms Used

The following classification algorithms were implemented:

1. Logistic Regression
2. Random Forest
3. Support Vector Machine (SVM)
4. XGBoost

## Model Performance

| Model | Accuracy |
|---|---|
| Logistic Regression | 85.25% |
| Random Forest | 83.61% |
| SVM | 86.89% |
| XGBoost | 81.97% |

## Best Performing Model

Support Vector Machine (SVM) achieved the highest accuracy of 86.89% and was selected as the final prediction model.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## Project Workflow

1. Data Collection
2. Data Exploration and Visualization
3. Data Preprocessing
4. Feature Scaling
5. Model Training
6. Model Evaluation
7. Disease Prediction

## Files Description

| File | Description |
|---|---|
| Disease_Prediction.ipynb | Complete ML implementation |
| disease_prediction_model.pkl | Trained SVM model |
| scaler.pkl | Feature scaling object |
| heart.csv | Dataset |
| requirements.txt | Required Python libraries |

## Author

Sadia Afrin Suchi

Machine Learning Internship Project - CodeAlpha
