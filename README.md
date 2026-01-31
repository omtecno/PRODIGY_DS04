# 🏦 Bank Marketing Decision Tree

## Overview
This project uses **Machine Learning (Decision Tree Classifier)** to predict whether a customer will subscribe to a **Bank Term Deposit**.  
It includes data analysis, preprocessing, model training, and evaluation.

---

## Dataset
- **Source:** UCI Bank Marketing Dataset  
- **Records:** 45,211  
- **Features:** 16 Inputs + 1 Target  
- **Target Variable:** `y` (Yes/No)  
- **Imbalance:** 11.7% Yes | 88.3% No  

---

## Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## Methodology
- Data Cleaning & EDA  
- Label Encoding  
- Outlier Removal (IQR)  
- Train/Test Split (75/25)  
- Decision Tree (Gini)

---

## Results
- **Accuracy:** 89%  
- **ROC-AUC:** 0.91  
- **Precision (Yes):** 0.58  
- **Recall (Yes):** 0.52  

---

## How to Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
git clone https://github.com/omtecno/PRODIGY_DS04/tree/main

jupyter notebook
