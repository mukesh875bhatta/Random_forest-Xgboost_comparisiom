# Random_forest-Xgboost_comparision
# Breast Cancer Classification: Random Forest vs XGBoost

## Project Overview

This project compares the performance of two popular ensemble machine learning algorithms **Random Forest** and **XGBoost**  on the **Breast Cancer Wisconsin (Diagnostic)** dataset. The goal is to classify tumors as **malignant** or **benign** based on features extracted from digitized images of fine needle aspirate (FNA) samples.

---

## Dataset

- Source: [Breast Cancer Wisconsin (Diagnostic) Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- Number of samples: 569
- Features: 30 numeric features describing cell nuclei
- Target: Diagnosis (`M` = malignant, `B` = benign)

---

## Algorithms Used

- **Random Forest Classifier**  
  A bagging ensemble method using multiple decision trees for classification.

- **XGBoost Classifier**  
  An optimized gradient boosting framework designed for speed and performance.

---

## Methodology

1. Data preprocessing including encoding target labels and dropping irrelevant columns.
2. Splitting data into training and test sets.
3. Training Random Forest and XGBoost classifiers.
4. Evaluating models using metrics: Accuracy, Precision, Recall, F1-score.
5. Visualizing results with confusion matrices and performance comparison plots.

---

## Performance Summary

| Metric    | Random Forest | XGBoost    |
|-----------|---------------|------------|
| Accuracy  | 0.97          | 0.98       |
| Precision | 0.97          | 0.98       |
| Recall    | 0.96          | 0.97       |
| F1-Score  | 0.97          | 0.97       |


