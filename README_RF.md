Heart Disease Prediction using Random Forest Classifier

This project focuses on the early detection of cardiovascular diseases using a Random Forest Ensemble Model. By analyzing clinical patient data, the model provides highly accurate predictions to assist in clinical decision-making.

📌 Project Overview
Heart disease is a leading cause of mortality worldwide. This implementation leverages the power of Machine Learning to identify risk factors and predict heart conditions with high reliability.

Why Random Forest?

Robustness: Handles outliers and noise in medical data effectively.

Accuracy: Combines multiple decision trees to reduce variance.

Non-linear Data: Captures complex interactions between clinical features like cholesterol, age, and blood pressure.

📊 Performance Evaluation
The model was evaluated using standard classification metrics, yielding exceptional results that demonstrate its readiness for diagnostic support.

1. Confusion Matrix
The confusion matrix below illustrates the model's ability to minimize False Negatives, which is critical in healthcare.

[INSERT IMAGE HERE: results/confusion_matrix.png]
Figure 1: Confusion Matrix showing 92.7% overall accuracy.

True Positives (32): Correctly identified heart disease cases.

True Negatives (44): Correctly identified healthy individuals.

Low False Negatives (3): High sensitivity, ensuring fewer cases go undiagnosed.

2. ROC Curve & AUC Score
The Receiver Operating Characteristic (ROC) curve evaluates the model's discriminative power.

[INSERT IMAGE HERE: results/roc_curve.png]
Figure 2: ROC Curve with an AUC of 0.96.

An AUC of 0.96 indicates that the model has a 96% probability of correctly ranking a random positive instance higher than a random negative one, showcasing its superior performance.

🛠️ Tech Stack & Methodology
Language: Python 3.x

Libraries: Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn

Algorithm: Random Forest (Ensemble Learning)

Validation: K-Fold Cross-Validation & Bootstrap Aggregating (Bagging)

📂 Repository Structure
Plaintext
├── data/               # Patient datasets
├── notebooks/          # Jupyter notebook for model training
├── results/            # Performance plots (Confusion Matrix, ROC Curve)
├── models/             # Saved .pkl model files
└── README.md           # Project documentation
🚀 How to Run
Clone the repository:

Bash
git clone https://github.com/yourusername/heart-disease-prediction-rf.git
Install dependencies:

Bash
pip install -r requirements.txt
Execute the notebook:
Open notebooks/heart_disease_rf.ipynb in Jupyter or VS Code to see the full implementation.

👨‍💻 Author
EKANAYAKA E M L M  IT Number: IT22897558 Faculty of Computing, SLIIT
