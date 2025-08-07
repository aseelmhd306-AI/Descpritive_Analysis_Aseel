# 💳 Credit Card Fraud Detection

This project applies machine learning techniques to identify fraudulent credit card transactions using a real-world dataset.

## 📂 Dataset Description
- `step`: Time step (1 step = 1 hour)
- `Amount`: Transaction amount
- `Category`, `Age`, `Gender`: Customer details
- `Fraud`: Target variable (0 = legit, 1 = fraud)

## ⚙️ Methods Used
- Data cleaning and preprocessing
- Feature engineering
- Handling class imbalance using SMOTE
- Model training with Logistic Regression, Random Forest, and XGBoost
- Evaluation using F1-score and AUC

## 🏆 Best Model
- **Random Forest model ** with F1-score:36.36% and AUC: 73.39%
  
- 🎯 Why is Random Forest the best?
1️⃣ Balanced performance:

Highest F1-Score (36.36%) - Best balance between precision and recall
Reasonable precision (50%) - For every two warnings, one is correct
Acceptable recall (28.57%) - Detects a quarter of frauds

## 📌 How to Run
1. Open `fraud01.ipynb`
2. Run all cells step-by-step


---

> Made with ❤️ by Aseel
