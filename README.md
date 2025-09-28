# Credit Risk Prediction

## 📌 Project Overview
Machine learning project to predict **loan default risk** using the **loan_data_2007_2014 dataset**.  
Covers data cleaning, feature engineering, EDA, preparation, model training, and evaluation.  

---

## 🎯 Problem Statement
Financial institutions need to assess **loan default risk** before approval.  
Goal: classify loans into:  
- **Fully Paid (0)**  
- **Charged Off (1)**  

---

## 🛠 Methods
- **Models:** Logistic Regression (baseline) & Random Forest.  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, ROC-AUC.  

---

## 📊 Results
- Logistic Regression → Accuracy: ~100%, ROC-AUC: 0.999  
- Random Forest → Accuracy: ~100%, ROC-AUC: 1.000  
- **Random Forest chosen as final model** due to slightly better performance.  

---

## ✅ Conclusion
The project shows that **interest rate, grade, and DTI** are key indicators of loan default risk.  
Random Forest provides the most consistent results and can support better **credit risk management**.  
