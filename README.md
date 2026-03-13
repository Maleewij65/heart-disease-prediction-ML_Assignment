# Heart-disease-prediction-ML_Assignment
# Heart Disease Prediction using Support Vector Machine (SVM)

This project implements a **Support Vector Machine (SVM)** based machine learning model to predict the presence of heart disease using a structured heart disease dataset. The objective of the model is to classify patients into two categories: **presence of heart disease** or **absence of heart disease**, based on several medical attributes.

The workflow includes data preprocessing, feature engineering, model training, hyperparameter tuning, and performance evaluation. The model is developed and tested using **Python in Google Colab** with popular machine learning and data analysis libraries.

---

## Project Workflow

The following steps were carried out to build the SVM model:

1. **Data Preprocessing**

   * Removal of invalid or inconsistent values
   * Handling dataset quality issues

2. **Feature Engineering**

   * Standardization of numerical features using `StandardScaler`
   * One-hot encoding of categorical features using `OneHotEncoder`

3. **Model Development**

   * Implementation of the **Support Vector Machine (SVM)** classifier
   * Creation of a preprocessing and classification pipeline

4. **Hyperparameter Tuning**

   * Optimization of model parameters (`C`, `gamma`, `kernel`)
   * Use of **GridSearchCV with 5-fold cross-validation**

5. **Model Evaluation**

   * Accuracy
   * Precision
   * Recall
   * F1-score
   * Confusion Matrix
   * ROC Curve and AUC Score
   * Learning Curve Analysis

---

## Tools and Technologies

* **Python**
* **Google Colab**
* **Scikit-learn**
* **Pandas**
* **Matplotlib**
* **Seaborn**

---

## Repository Structure

```
Heart-Disease-Prediction
│
├── svm_model.ipynb        # Google Colab notebook with full implementation
├── heart.csv              # Dataset used for training and testing
├── README.md              # Project documentation
└── images                 # Generated evaluation plots
    ├── confusion_matrix.png
    ├── roc_curve.png
    └── learning_curve.png
```

---

## Objective

The goal of this project is to demonstrate how **Support Vector Machines can be applied to medical datasets for disease prediction**, while following a structured machine learning workflow including preprocessing, model optimization, and performance evaluation.


