## About Dataset

This dataset contains various health indicators and risk factors related to heart disease. It includes demographic, lifestyle, and clinical measurements such as age, blood pressure, cholesterol levels, smoking habits, and exercise patterns.

The dataset is suitable for analyzing heart disease risk, identifying key contributing factors, and building predictive machine learning models in a healthcare context.

## Feature Columns

Age: Age of the individual

Gender: Male or Female

Blood Pressure: Systolic blood pressure

Cholesterol Level: Total cholesterol level

Exercise Habits: Low, Medium, or High

Smoking: Yes or No

Family Heart Disease: Family history of heart disease (Yes or No)

Diabetes: Yes or No

BMI: Body Mass Index

High Blood Pressure: Yes or No

Low HDL Cholesterol: Yes or No

High LDL Cholesterol: Yes or No

Alcohol Consumption: None, Low, Medium, or High

Stress Level: Low, Medium, or High

Sleep Hours: Average sleep hours per day

Sugar Consumption: Low, Medium, or High

Triglyceride Level: Triglyceride measurement

Fasting Blood Sugar: Fasting blood sugar level

CRP Level: C-reactive protein (inflammation marker)

Homocysteine Level: Homocysteine concentration

Heart Disease Status: Target variable (Yes or No)

## Models Used

1. Logistic Regression (Baseline Model)
2. Random Forest Classifier
3. Gradient Boosting Classifier
4. XGBoost

## Methods Used

1. Stratified K-Fold Cross Validation
2. Synthetic Minority Over-sampling Technique (SMOTE)
3 .Hyperparameter tuning using Grid Search

## Evaluation Metrics

1. Precision
2. Recall
3. F1 Score

## Note:
In clinical prediction problems, recall is a critical metric because failing to identify a patient with heart disease can have serious consequences. Therefore, this project prioritizes recall while also maintaining strong overall accuracy.