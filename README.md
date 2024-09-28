# Heart Disease Prediction

## Overview
This project aims to predict the presence of heart disease in patients using machine learning techniques. The dataset used for this project is sourced from the UCI Machine Learning Repository, containing various medical attributes of patients.

## Dataset
The dataset consists of several medical features and a target variable indicating the presence (1) or absence (0) of heart disease. The key features include:
- **age**: Age of the patient
- **sex**: Gender of the patient (1 = male, 0 = female)
- **chest pain type**: Type of chest pain experienced
- **resting bp**: Resting blood pressure
- **cholesterol**: Serum cholesterol in mg/dl
- **fasting blood sugar**: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- **resting ecg**: Resting electrocardiographic results
- **max heart rate**: Maximum heart rate achieved
- **exercise angina**: Exercise induced angina (1 = yes; 0 = no)
- **oldpeak**: ST depression induced by exercise relative to rest
- **ST slope**: Slope of the peak exercise ST segment

## Models Used
-**Swarm Artificial Neural Network (Swarm-ANN)**: A neural network optimized using swarm intelligence.

-**Logistic Regression**: A linear model for binary classification.

-**Random Forest**: An ensemble model that combines multiple decision trees for classification.

-**Support Vector Machine (SVM)**: A model that finds the optimal hyperplane for classification.


## Results
The models were evaluated using metrics such as accuracy, precision, recall, and F1-score. The following are the accuracies of the models tested:

-**Swarm-ANN**: 76.47%

-**Logistic Regression**: 86.13%

-**Random Forest**: 94.12%

-**SVM**: 84.45%

## Conclusion
The project demonstrates various machine learning techniques for predicting heart disease. The Random Forest model outperformed the others in this evaluation.
