💳 Credit Card Fraud Detection

📌 Overview

This project aims to detect fraudulent credit card transactions using Machine Learning techniques.
It focuses on identifying anomalies/outliers in transaction data to classify transactions as fraudulent or legitimate.

🚀 Features
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Handling Imbalanced Dataset
Outlier Detection Techniques
Machine Learning Model for Classification
Model Evaluation
🛠️ Tech Stack
Programming: Python
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Model Saving: Joblib
📂 Project Structure
""" Credit-Card-Fraud-Detection/
│
├── data/
│   └── creditcard.csv
│
├── notebook/
│   ├── EDA.ipynb
│   ├── modeling.ipynb
│
├── src/
│   ├── preprocess.py
│   ├── train.py
│   ├── evaluate.py
│   └── models/
│       └── model.pkl
│
├── requirements.txt
└── README.md """
⚙️ Installation
## Clone repository
git clone https://github.com/your-username/credit-card-fraud-detection.git

## Navigate to folder
cd credit-card-fraud-detection

## Create environment (optional)
conda create -n fraud_env python=3.10
conda activate fraud_env

## Install dependencies
pip install -r requirements.txt
▶️ Run the Project
1. Train Model
python src/train.py
📊 Model Workflow
Data Cleaning
Handling Missing Values
Feature Scaling (important for fraud detection)
Handling Imbalanced Data (SMOTE / undersampling)
Model Training
Prediction
🤖 Algorithms Used
Logistic Regression
Random Forest
Isolation Forest (Outlier Detection)
One-Class SVM
📈 Evaluation Metrics
Accuracy
Precision
Recall
F1 Score
ROC-AUC

⚠️ Note: Accuracy is not reliable for imbalanced data. Focus on Precision, Recall, and ROC-AUC.

🧠 Use Case
Detect fraudulent transactions in real-time
Reduce financial losses
Improve security systems in banking
