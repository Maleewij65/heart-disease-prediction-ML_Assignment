# Heart-disease-prediction with XGBoost - ML_Assignment

This project focuses on predicting of heart disease using machine learning techniques. The model is built using XGBoost (Extreme Gradient Boosting) and evaluated with multiple performance metrics.

Data set: heart.csv
The dataset contains patient health related features such as:
  *Age
  *Resting Blood Preasure
  *Cholesterol
  *Max Heart Rate
  *Oldpeak
  *Other categorical attributes

Target Variable:
  HeartDisease ( 0 = N0, 1 = Yes)

**Project Workflow**

01. Data Preprocessing
  *Removed invalid values (eg: Cholesterol = 0)
  *Handled missing values
  *Outlier removal using IQR method
  *One - hot encoding for categorical variables
  *Feature scaling using StandardScaler

02. Model Building
  *Train - test split (80% training, 20% testing)
  *Model used - XGBClassifier

03. Model Evaluation
  *Metrics used - Accuracy, Precision, Recall, F1 Score, Confusion Matrix, ROC Curve and AUC Score

04. Hyperparameter Tuning
  *Used GridSearchCV with parameters:
      - max_depth, learning_rate, n_estimators
  *Selected best model based on accuracy

05. Cross Validation
  * Performed 5 - fold cross -  validation
  * Evaluated - Accuracy, Precision, Recall, F1 Score

06. Visualization
  * Confusion Matrix, Feature Importance, Target Variable Distribution, ROC Curve

Results:
*Achieved strong classification performance using XGBoost.
*Improved accuracy after hyperparameter tuning.
*Key features influencing predictions were identified.
  
