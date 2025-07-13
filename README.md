# 🧠 Final Project – Machine Learning: Cyber Attack Classification

This project builds a full ML pipeline to detect and classify various types of network traffic, including cyberattacks such as DDoS, Mirai, Recon, and more.

## 🔍 Objective
Classify network traffic as normal or malicious based on provided features using supervised machine learning.

## 📁 Files Included
- `Final_Project_ML_Phase_2.ipynb` – Main notebook containing:
  - Data cleaning
  - Exploratory data analysis
  - Feature selection
  - SMOTE oversampling
  - Multiple ML models (RandomForest, XGBoost, LightGBM, Stacking)
  - Final prediction and CSV submission
- `train.csv` – Labeled dataset used for training and evaluation.
- `test.csv` – Unlabeled dataset used for final prediction.
- `best_submission.csv` – Submission file containing model predictions.

## 📊 Models Used
- Random Forest
- Balanced Random Forest
- XGBoost
- LightGBM
- Stacking Classifier (Ensemble of the above)

## 🧪 Evaluation Metric
- Accuracy
- Classification Report (Precision, Recall, F1-score)

## 📦 Requirements
See [`requirements.txt`](requirements.txt)

## 🚀 Run Instructions
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
Run the notebook Final_Project_ML_Phase_2.ipynb using Jupyter or Colab.

📌 Notes
Feature selection was done using SelectKBest.

SMOTE used to handle class imbalance.

Final submission uses predictions from the Random Forest model (can be switched).

Author: Ahmed Niazy Mahdy
University: Zewail City – Computer Science & AI


