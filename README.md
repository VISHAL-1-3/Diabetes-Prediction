# 🩺 Diabetes Prediction System  
### End-to-End Healthcare Analytics & Decision Support Model  

---

## 📌 Overview  
This project focuses on building a predictive analytics solution to identify high-risk diabetes patients using clinical data.  
The goal is not only to predict outcomes but to enable **data-driven decision-making** for healthcare and pharmaceutical use cases.

---

## 🎯 Problem Statement  
Early detection of diabetes is critical for improving patient outcomes and reducing long-term healthcare costs.  

This project aims to:  
- Predict diabetes risk using patient health data  
- Identify high-risk individuals  
- Support targeted intervention strategies  

---

## 💡 Business Impact  
- Enables **targeted outreach** for high-risk patients  
- Improves **campaign efficiency and ROI**  
- Reduces unnecessary healthcare costs  
- Supports **preventive care strategies**  

---

## 🗂️ Dataset  
- **Source:** Pima Indians Diabetes Dataset  
- **Records:** 768 patients  
- **Features:** Glucose, BMI, Age, Blood Pressure, Insulin, etc.  

---

## ⚙️ Approach  

### 🔹 1. Data Cleaning  
- Handled invalid zero values in medical features  
- Replaced with median values for robustness  

### 🔹 2. Exploratory Data Analysis  
- Correlation analysis to identify key relationships  
- Visualization of feature interactions  

### 🔹 3. Model Building  
- Random Forest Classifier  
- Hyperparameter tuning using GridSearchCV  
- Cross-validation for robustness  

### 🔹 4. Model Optimization  
- Applied **class weighting** to handle imbalance  
- Adjusted classification threshold to improve recall  
- Focused on minimizing false negatives  

---

## 📊 Model Performance  

| Metric | Value |
|------|------|
| Accuracy | ~76% |
| ROC-AUC | ~0.82 |
| Recall (Diabetic Class) | ~78% |

> Note: Model optimized for **recall**, as missing high-risk patients is more critical in healthcare scenarios.

---

## 🔍 Key Insights  
- **Glucose, BMI, and Age** are the most important predictors  
- High-risk patients can be effectively identified using probability thresholds  
- Data-driven segmentation improves decision-making  

---

## 🔥 Risk Segmentation  
Patients are categorized into:  
- 🔴 High Risk  
- 🟡 Medium Risk  
- 🟢 Low Risk  

This enables prioritized intervention strategies.

---

## 💰 Business Simulation  

| Metric | Value |
|------|------|
| Campaign Cost | ₹5,000 |
| Potential Benefit | ₹25,000 |
| Net Gain | ₹20,000 |

👉 Demonstrates **~5x ROI** through targeted outreach  

---

## 🛠️ Tech Stack  
- Python (Pandas, NumPy)  
- Scikit-learn  
- Matplotlib, Seaborn  
- Machine Learning (Random Forest)  

---

## 🚀 Key Learnings  
- Importance of **recall over accuracy** in healthcare  
- Handling imbalanced datasets using class weighting  
- Translating ML outputs into **business decisions**  
- Building end-to-end analytics pipelines  

---

## 📂 Project Structure  

---

## 🔗 GitHub Link  
[View Project](https://github.com/VISHAL-1-3/Diabetes-Prediction/blob/main/Diabetes_Prediction.ipynb)

---

## 🎯 Conclusion  
This project demonstrates how machine learning can go beyond prediction to deliver **actionable insights and business value**.  

By integrating analytics with decision-making, the model helps organizations improve outcomes while optimizing costs.

---
