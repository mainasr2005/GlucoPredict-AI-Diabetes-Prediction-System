# 🩺 GlucoPredict AI

A Machine Learning project for predicting diabetes risk using patient health data and Support Vector Machine (SVM).

## 📌 Overview

GlucoPredict AI aims to predict whether a patient is likely to have diabetes based on medical measurements and health indicators. The project applies data preprocessing, exploratory data analysis, feature scaling, and machine learning techniques to build an accurate prediction model.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🔍 Project Workflow

- Data Exploration and Analysis
- Data Cleaning
- Outlier Handling using IQR
- Correlation Analysis
- Feature Scaling using StandardScaler
- Train-Test Split
- Model Training
- Model Evaluation

## 🤖 Model Used

Support Vector Machine (SVM)

```python
SVC(
    kernel='rbf',
    C=100,
    gamma=0.1
)
