# Credit Card Fraud Detection

A machine learning-based app to detect fraudulent credit card transactions using real anonymized data and a trained XGBoost model. This project combines data science, explainability, and a simple web UI via Streamlit.

---

## 🚀 Features

- Upload a CSV file with transactions
- Predict whether each transaction is **Fraudulent** or **Genuine**
- Displays **fraud probability**
- Download the results with predictions
- (Optional) Add SHAP interpretability

---

## 📊 Model Used

- **Algorithm**: XGBoost Classifier, Random Forest
- **Handling Imbalance**: SMOTE oversampling
- **Evaluation Metrics**: Recall, F1-Score, AUC

---

## 📁 Files

| File | Description |
|------|-------------|
| `app.py` | Streamlit app script |
| `model_xgb.pkl` | Trained XGBoost model |
| `requirements.txt` | Required packages for running locally or on Streamlit Cloud |
| `README.md` | This file |

---

## 🧪 Run Locally

1. Clone this repo  
2. Install dependencies  
   ```bash
   pip install -r requirements.txt

