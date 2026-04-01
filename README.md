# Heart-disease-prediction-ML_Assignment

**Group Details**

**IT22339324 - Wijerathne M.A.S.M**
**IT22923806 - Kodisinghe H.R**
**IT22325778 - Fernando W.P.N. S**
**IT22897558 - Ekanayaka E.M.L.M**

For this project, we used the **https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction** obtained from Kaggle. The dataset consists of 918 patient records and 12 clinical features, including both numerical and categorical variables. These features represent key health indicators such as age, cholesterol levels, resting blood pressure, and heart rate, which are commonly used in cardiovascular diagnosis.

**PROJECT OVERVIEW**
This project focuses on predicting the presence of heart disease using machine learning techniques. Cardiovascular diseases remain one of the leading causes of death worldwide, making early detection extremely important. By leveraging structured patient data such as age, cholesterol levels, blood pressure, and other clinical indicators, we aim to build reliable predictive models that can assist in medical decision-making.

The dataset used in this project is the Heart Failure Prediction dataset, which contains 918 patient records with 12 clinical features. Before training the models, the data was carefully preprocessed, including handling invalid values, encoding categorical variables, scaling numerical features, and splitting into training and testing sets.

The main objective is to compare multiple machine learning algorithms and identify the most effective model for heart disease prediction based on performance metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

**Project Components**

**01. CatBoost Model**

CatBoost is a gradient boosting algorithm developed by Yandex, specifically designed to handle categorical features efficiently without requiring extensive preprocessing like one-hot encoding.
In this project, CatBoost serves as the fourth component, providing an additional advanced boosting approach. One of its key advantages is its ability to reduce overfitting and handle categorical data more effectively than traditional models.
CatBoost improves model stability and often delivers strong performance with minimal parameter tuning. Its inclusion allows for a more comprehensive comparison of modern machine learning techniques and helps validate whether advanced boosting methods outperform traditional algorithms.

**02.XGBoost**

XGBoost (Extreme Gradient Boosting) is a powerful boosting algorithm that builds trees sequentially, where each new tree corrects the errors of the previous ones. It is known for its efficiency and high performance on structured datasets.
In our implementation, XGBoost demonstrated competitive results with good precision and balanced classification performance. It also provided useful insights through feature importance analysis, highlighting key factors influencing heart disease prediction.

**03.Support Vector Machine (SVM)**

Support Vector Machine is a supervised learning algorithm that finds the optimal boundary (hyperplane) to separate different classes. It is particularly effective in high-dimensional spaces and can model complex relationships using kernel functions.
The SVM model in this project achieved moderate performance with a good balance between precision and recall. With proper hyperparameter tuning, it was able to effectively classify patients, though it slightly underperformed compared to ensemble methods.

**04.Random Forest Model**

Random Forest is an ensemble learning algorithm that builds multiple decision trees and combines their outputs to improve prediction accuracy. It is particularly useful for handling datasets with mixed data types and reducing overfitting.
In this project, Random Forest showed strong and consistent performance. It achieved high accuracy and recall, making it highly effective in identifying patients with heart disease. This is especially important in healthcare applications where missing a positive case can have serious consequences.
