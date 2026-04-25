# Lab9-Decision-Trees-and-Random-Forest-Project-loan_data-

## Overview
This project applies machine learning techniques (Decision Tree and Random Forest) to predict whether a loan will be fully paid or not.

---

## Problem Type
Supervised Machine Learning – Classification

---

## Objective
The objective of this project is to:
- Build a **Decision Tree model**
- Build a **Random Forest model**
- Compare their performance in predicting loan repayment status  
- Focus on detecting **high-risk loans (not fully paid)**

---

## Dataset Information
- **Dataset:** `loan_data.csv`
- **Target Variable:** `not.fully.paid`

### Features include:
- credit.policy  
- purpose *(categorical)*  
- int.rate  
- installment  
- log.annual.inc  
- dti  
- fico  
- revol.bal  
- revol.util  
- and more  

---

## Libraries Used
```python
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---


## Key Results
- Random Forest achieved higher overall accuracy
- However, it performed poorly in detecting the minority class (not fully paid)
- The decision tree showed better performance in identifying high-risk loans


---


## 🔹 Conclusion
Although Random Forest achieved higher accuracy, Decision Tree performed better in detecting unpaid loans. This highlights the importance of evaluating models using metrics like recall and F1-score, especially with imbalanced data.

