# EasyMoney – Customer Propensity Prediction & Segmentation with Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-15B5B0?style=for-the-badge&logo=xgboost&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

## 🔎 Project Overview

**EasyMoney** is an end-to-end **Data Science project** focused on improving the profitability of banking marketing campaigns using **Machine Learning**.

The system predicts **customer purchase propensity** for high-value financial products and performs **customer segmentation** to enable targeted marketing strategies, achieving a **significantly higher ROI** compared to traditional mass-marketing approaches.

---

## 🎯 Business Objectives

- **Propensity Prediction:** Identify customers most likely to subscribe to high-value products (e.g. Pension Plans, Long-Term Deposits).
- **Customer Segmentation:** Cluster customers into homogeneous profiles to enable personalized campaigns and cross-selling.
- **ROI Optimization:** Quantify the economic impact of ML-driven marketing strategies versus traditional campaigns.

---

## 🧠 Methodology

The project follows a structured **Data Science pipeline**:

### 1️⃣ Data Cleaning & Feature Engineering  
**Notebook:** `1-data_cleaning.ipynb`  
- Dataset with **~5.9M records**
- Missing value handling for key categorical variables
- Memory optimization through data type casting

### 2️⃣ Propensity Modeling (Supervised Learning)  
**Notebook:** `2-classification_model.ipynb`  
- Algorithms: Random Forest, XGBoost  
- Evaluation metric: **AUC-ROC**
- Best result: **AUC = 0.93** for Long-Term Deposit prediction  
- Feature importance analysis (age, acquisition channel, etc.)

### 3️⃣ Customer Segmentation (Unsupervised Learning)  
**Notebook:** `3-clustering.ipynb`  
- K-Means clustering on behavioral and demographic features  
- Identification of **6 actionable customer segments**
- Business interpretation of each cluster

### 4️⃣ Business Use Case & ROI Analysis  
**Notebook:** `4-use_case.ipynb`  
- Simulation of a real marketing campaign  
- Comparison: ML-driven targeting vs traditional strategy  
- **Result:**  
  - ML campaign: ~27.3M € captured  
  - Traditional campaign: ~1.2M €  
  - ROI improvement: **>20x**

---

## 📊 Key Results

- **AUC-ROC:** 0.93  
- **ROI:** More than 20x improvement  
- **Impact:** Direct contribution to EBITDA by reducing acquisition costs

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/easymoney.git
pip install pandas numpy scikit-learn xgboost matplotlib seaborn
