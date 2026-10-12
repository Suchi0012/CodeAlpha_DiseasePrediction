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

## Machine Learning Algorithms Used

This project applies multiple supervised machine learning classification algorithms to predict the possibility of heart disease.

The following models were implemented and evaluated:

| Model | Accuracy |
|------|----------|
| Logistic Regression | 85.25% |
| Random Forest | 83.61% |
| Support Vector Machine (SVM) | 86.89% |
| XGBoost | 81.97% |

Among all tested models, **Support Vector Machine (SVM)** achieved the highest accuracy on the test dataset.

---

## Dataset Information

Dataset Used:

- Heart Disease Dataset from UCI Machine Learning Repository

The dataset contains medical information of patients including:

- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol level
- Fasting blood sugar
- Resting ECG results
- Maximum heart rate achieved
- Exercise induced angina
- ST depression
- Number of major vessels
- Thalassemia information

The target variable represents:

- 0 → No heart disease
- 1 → Presence of heart disease

---

## Project Workflow

The project follows these machine learning steps:

1. Data Collection
2. Data Exploration and Visualization
3. Data Preprocessing
4. Feature Scaling
5. Dataset Splitting into Training and Testing sets
6. Model Training
7. Model Evaluation
8. Disease Prediction

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## Installation

Clone this repository:

```bash
git clone https://github.com/Suchi0012/CodeAlpha_DiseasePrediction.git
