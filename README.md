# 💳 Credit Card Fraud Detection

A machine learning project developed during my internship at **IIT Kanpur**, focused on detecting fraudulent credit card transactions using real-world anonymized data. This project leverages the **Random Forest** algorithm to classify transactions as fraudulent or legitimate, helping address the growing challenge of financial fraud in digital payment systems.

---

## 📄 Report Summary

### 🧾 Introduction

In this report, I present the development and implementation of a **credit card fraud detection system**. I outline the process of analyzing a dataset, exploring patterns, and building a predictive model using the **Random Forest algorithm**. This report highlights the steps taken, insights gained, and the significance of the project in addressing **financial fraud challenges**.

---

### 🛠️ Project Development

I began by loading the dataset and performing **Exploratory Data Analysis (EDA)** to understand data distribution and identify potential features indicative of fraudulent transactions.  
Subsequently, I implemented the **Random Forest classifier**, splitting the data into **training and testing sets**, training the model, and evaluating its performance using relevant metrics and visualizations.

---

### 📈 Results Analysis

The Random Forest model achieved strong performance in detecting fraud, with an accuracy of **99.96%**.  
Through visualizations and statistical analysis, I gained insights into key indicators of fraudulent behavior and the importance of specific features (like transaction amount and timing) in model predictions.

---

### ✅ Conclusion

This project demonstrates the effectiveness of **machine learning**, particularly Random Forest, in **detecting credit card fraud**.  
By applying data-driven techniques, we can enhance fraud detection systems, **mitigate financial risks**, and protect consumer trust.  
As fraud tactics continue to evolve, ongoing research and technological improvements are essential for maintaining secure and reliable transaction systems.

---

**— Summary and Analysis by Panendra Rao. J**

---

## 📊 Dataset Overview

- Source: Public dataset from Kaggle  
- Records: `284,807` transactions  
- Fraudulent: Only `492` (≈ 0.17%)  
- Features: 30 numerical inputs (transformed via PCA), including `Amount`, `Time`, and `Class`

---

## 🔍 Methodology Overview

- **EDA**: Used `seaborn` and `matplotlib` to explore class imbalance and data distribution  
- **Model**: Trained a `RandomForestClassifier` using `scikit-learn`  
- **Evaluation**: Used accuracy, confusion matrix, and feature importance plots  
- **Result**: Achieved **99.96% accuracy** with low false negatives  

---

## ⚙️ Technologies Used

| Component            | Tools/Libraries         |
|----------------------|-------------------------|
| Programming Language | Python 3.8+             |
| Data Handling        | pandas                  |
| Visualization        | matplotlib, seaborn     |
| Machine Learning     | scikit-learn (RandomForestClassifier) |
| Notebook Environment | Jupyter Notebook        |

---

