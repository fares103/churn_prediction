# 📊 Customer Churn Prediction

This project uses **Logistic Regression** to predict whether a customer will churn based on historical customer data. It also includes a rule-based system to send targeted discounts to customers who are at risk of leaving.

---

## 🧠 Project Overview

- **Goal**: Predict customer churn (whether they will leave the service).
- **Model**: Logistic Regression with class balancing.
- **Dataset**: Telco Customer Churn dataset.
- **Tools Used**: Python, NumPy, Pandas, Scikit-learn.

---

## 🗂️ Project Structure
Customer-Churn-Prediction/
│
├── README.md                 # Project description
├── requirements.txt          # Python dependencies
├── data/
│   ├── raw/                  # Original/raw dataset
│   └── processed/            # Cleaned and feature-engineered data
│
├── notebooks/
│   ├── 01_data_exploration.ipynb   # EDA and visualization
│   ├── 02_data_cleaning.ipynb      # Cleaning & feature engineering
│   └── 03_modeling.ipynb           # Model training and evaluation
│
├── src/                      # Python scripts
│   ├── data_preprocessing.py  # Functions for cleaning & preprocessing
│   ├── train_model.py         # Model training script
│   └── evaluate_model.py      # Model evaluation script
│
├── models/                   # Saved/trained models (pickle files)
│
└── reports/
    └── figures/              # Plots, charts, and visualizations


