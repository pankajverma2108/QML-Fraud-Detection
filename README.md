# 🧠 Quantum Machine Learning for Insurance Claim Fraud Detection: A Hybrid Approach

## 📌 Overview

This project presents a hybrid quantum-classical machine learning framework to detect **fraudulent insurance claims**. It leverages the strength of **Quantum Support Vector Classifier (QSVC)** for complex pattern recognition and combines it with a **Random Forest (RF)** model for robust, interpretable decision-making.

---

## 🎯 Objective

> To improve fraud detection accuracy in imbalanced datasets by integrating quantum feature extraction and classical classification — ensuring better generalization, interpretability, and scalability.

---

## 🗃️ Dataset

- **Source:** [Kaggle - Insurance Claims Fraud Data](https://www.kaggle.com/datasets/mastmustu/insurance-claims-fraud-data)

---

## 🔧 Technologies Used

- Python 3.10  
- [Qiskit](https://qiskit.org/) (QSVC, ZZFeatureMap, etc.)  
- Scikit-learn  
- PyTorch  
- SHAP (for interpretability)  
- Matplotlib / Seaborn  

---

## ⚙️ Methodology
- Data preprocessing and feature encoding
- Dimensionality reduction using PCA
- Model 1: Train QSVC using ZZFeatureMap
- Model 2: Train VQC (EstimatorQNN + TorchConnector)
- Model 3 (Hybrid):
  - Use QSVC to flag high-risk claims (fraud)
  - Reclassify low-risk claims using Random Forest
- Compare metrics: Accuracy, F1-score, Precision, Recall
- Use SHAP for model interpretability
