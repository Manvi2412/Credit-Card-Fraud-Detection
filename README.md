# 💳 Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent credit card transactions using classification algorithms on an imbalanced dataset.

## 📊 Project Overview

- Developed a binary classification model to distinguish between legitimate and fraudulent transactions.
- Addressed class imbalance using oversampling techniques like SMOTE.
- Evaluated model performance using metrics suited for imbalanced data.

## 🛠️ Tools & Technologies

- **Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, imbalanced-learn  
- **Environment**: Jupyter Notebook / VS Code

## ⚙️ Models Used

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Performance Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC

## 🔍 Key Challenges & Solutions

- **Challenge**: Highly imbalanced data (~0.17% fraud cases)  
- **Solution**: Used SMOTE (Synthetic Minority Oversampling) to balance the dataset  
- Focused on **Recall** and **ROC-AUC** to reduce false negatives

