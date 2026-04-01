# CatBoost Classification Model for Heart Disease Prediction

## Overview

This project implements a CatBoost classification model to predict the presence of heart disease using clinical and medical attributes. The dataset consists of patient records with features such as age, cholesterol level, resting blood pressure, maximum heart rate, and ECG-related indicators.

CatBoost is a gradient boosting algorithm that performs exceptionally well on structured tabular data and can handle categorical features directly without extensive preprocessing, making it highly suitable for healthcare prediction tasks.

---

## Dataset

The dataset used in this project is the Heart Disease dataset.

- Total records: 918  
- Features: 11 input features and 1 target variable  

### Target Variable
- 0: No heart disease  
- 1: Presence of heart disease  

### Numerical Features
- Age  
- RestingBP  
- Cholesterol  
- FastingBS  
- MaxHR  
- Oldpeak  

### Categorical Features
- Sex  
- ChestPainType  
- RestingECG  
- ExerciseAngina  
- ST_Slope  

---

## Methodology

### Data Exploration
The dataset was analyzed to understand its structure, data types, and statistical properties. Missing values and duplicate records were checked, and class distribution was visualized.

### Data Preprocessing
- Removed unrealistic cholesterol values (equal to zero)  
- No missing values were found  
- Outliers were removed using the IQR method  
- Cleaned dataset prepared for modeling  

### Feature Handling
Categorical features were directly passed to the CatBoost model using the `cat_features` parameter, eliminating the need for manual encoding.

### Data Splitting
The dataset was split into training and testing sets using an 80:20 ratio with stratification to maintain class balance.

### Model Training
A CatBoost classifier was trained using predefined hyperparameters such as iterations, learning rate, and depth.

### Hyperparameter Tuning
GridSearchCV was used to find the optimal parameters:
- Depth  
- Learning rate  
- Iterations  

### Model Evaluation
The model was evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  
- Classification Report  

### Model Validation
- 5-fold cross-validation for stability  
- ROC curve and AUC score for classification performance  
- Feature importance analysis for interpretability  

---

## Results

### Test Set Performance
- Accuracy: 0.8777  
- Precision: 0.8507  
- Recall: 0.8906  
- F1 Score: 0.8702  

### Cross-Validation Performance
- CV Accuracy: 0.8655  
- CV Precision: 0.8617  
- CV Recall: 0.8469  
- CV F1 Score: 0.8521  

### ROC-AUC Score
- 0.9381  

---

## Key Insights

- The model performs well in identifying heart disease cases (high recall)  
- ST_Slope, MaxHR, and Oldpeak are the most important features  
- The model generalizes well based on consistent cross-validation results  

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- CatBoost  


