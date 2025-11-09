# 🧠 Ransomware Detection using Machine Learning  
### _Keras | Scikit-learn | Pandas | Python_  

---

## 🔍 Overview

This project focuses on building a **multi-model ransomware detection framework** using both **classical Machine Learning (ML)** and **Deep Learning (DL)** techniques.  
The goal is to detect ransomware activity—including **zero-day variants**—across diverse, real-world datasets with a focus on **binary (benign vs. ransomware)** and **family-level classification**.

The framework combines robust **feature engineering**, **data preprocessing**, and **model ensemble strategies** to improve detection accuracy and generalization performance.

---

## 🎯 Key Objectives

- Develop a **modular ransomware detection pipeline** supporting multiple models.  
- Explore **zero-day detection** and **cross-dataset generalization** using unseen ransomware families.  
- Benchmark classical ML models (Random Forest, XGBoost, SVM) against deep learning architectures (MLP, LSTM).  
- Compare performance using metrics such as **Accuracy**, **Precision**, **Recall**, **F1-score**, and **AUC-ROC**.

---

## 🧩 Datasets

The project references multiple real-world datasets for ransomware and benign samples, including:  
- **UGRansom Dataset**  
- **NSL-KDD**  
- **CICIDS 2017 / 2020**  
- **Custom Ransomware Family Samples** (collected for experimental zero-day validation)

Each dataset is preprocessed to extract network and system behavior features such as file operations, API calls, and packet-level statistics.

---

## ⚙️ Methodology

### 🧠 Pipeline Overview
1. **Data Collection & Cleaning** – Merging samples from heterogeneous ransomware datasets.  
2. **Feature Engineering** – Scaling, encoding, and selection of key discriminative features.  
3. **Modeling** –  
   - Classical ML: Random Forest, Gradient Boosting, SVM  
   - Deep Learning: MLP, LSTM (Keras)  
4. **Evaluation** – Using stratified cross-validation and zero-day splits to measure model resilience.  

---

## 📊 Metrics and Evaluation

| Metric | Description |
|--------|--------------|
| Accuracy | Overall detection performance |
| Precision / Recall | Measure false positives and detection completeness |
| F1-score | Balance between precision and recall |
| ROC-AUC | Detection capability under class imbalance |

---

## 🧰 Tech Stack

| Component | Tools Used |
|------------|-------------|
| Data Handling | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Deep Learning | Keras / TensorFlow |
| Visualization | Matplotlib, Seaborn |
| Metrics | Scikit-learn.metrics |

---
