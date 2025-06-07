# Predictive Maintenance Model

This repository contains a machine learning model for predictive maintenance using binary classification. 
The task is to predict potential equipment failure based on sensor data from the NASA CMAPSS dataset.

## 📊 Dataset

- **Source**: [NASA CMAPSS Dataset](https://www.nasa.gov/cmapps)
- Simulates turbofan engine degradation.

## 📌 Goal

Build a binary classification model that predicts whether a failure will occur soon.

## 🔧 Model Used

- Logistic Regression (baseline)
- Random Forest
- XGBoost (main model)

## 🔬 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

## ▶️ How to Run

```bash
pip install -r requirements.txt
jupyter notebook notebooks/predictive_maintenance.ipynb
