# Customer Churn Prediction

This project analyzes a global customer churn dataset to understand key factors contributing to customer attrition and build a predictive model. The goal is to help businesses identify customers at risk of leaving so they can take proactive retention measures.

## 📊 Dataset

- **Source**: Kaggle - Global Customer Churn Dataset
- **Rows**: 10,000+ customer records
- **Features**:
  - Demographics: Age, Gender, Geography
  - Financials: Credit Score, Balance, Tenure
  - Behavior: Number of Products, Active Member, Has Credit Card
  - Outcome: Churn (0 = No, 1 = Yes)

## 🔍 Analysis Highlights

- **Churn Rate**: ~20%
- **Top churn indicators**:
  - Fewer active products
  - Lower account balance
  - Shorter tenure
  - Being younger and not an active member

## 🧪 Model Summary

- **Model Used**: Random Forest Classifier
- **Accuracy**: 84.6%
- **ROC AUC**: 0.8579
- **Feature Importance**:
  - Balance
  - Age
  - Number of Products
  - Active Member Status

## 📈 Visuals & Insights

- Correlation heatmap of key features
- Bar plots showing churn by geography and product count
- ROC curve for model evaluation

## 📁 Files

- `Customer Churn.pdf` – Notebook exported to PDF with all code, visualizations, and results
- `churn.html` – Custom HTML summary page for GitHub Pages
- `README.md` – This file

## 📬 Contact

Created by Cheri Beda — for questions or collaboration, reach out via [cheri.l.beda@gmail.com](mailto:cheri.l.beda@gmail.com)
