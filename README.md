# Breast Cancer Data Analysis and Prediction Model

This repository contains the **Breast Cancer Data Analysis and Prediction Model**, a project aimed at analyzing breast cancer data and building machine learning models to predict whether a tumor is malignant or benign. The primary goal of this project is to support early detection through data-driven approaches, helping healthcare professionals make more informed decisions.

---

## 🚀 Features

- Comprehensive **Exploratory Data Analysis (EDA)**:
  - Visualization of feature distributions, correlations, and patterns.
  - Identification of key features influencing breast cancer diagnosis.

- Machine Learning Models:
  - Logistic Regression, Random Forest, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM).
  - Evaluation of model performance using accuracy, precision, recall, F1-score, and ROC-AUC.

- Reproducible Code:
  - Clean, modular, and well-documented scripts for analysis, preprocessing, and model training.

---

## 📊 Dataset

The dataset contains features extracted from images of fine needle aspirates of breast masses. It includes:

- **Features**:
  - Example: `radius_mean`, `texture_mean`, `perimeter_mean`, `smoothness_mean`, etc.
- **Target Variable**:
  - Binary classification: `Malignant` (1) or `Benign` (0).

The dataset is clean and ready for preprocessing, with no missing values.

---

## 🧠 Machine Learning Pipeline

### 1. Data Preprocessing
- Standardized the feature values using StandardScaler.
- Split the dataset into training (80%) and testing (20%) subsets.
- Handled class imbalance using stratified splits.

### 2. Exploratory Data Analysis (EDA)
- Visualized distributions of key features.
- Analyzed feature correlations using heatmaps.
- Identified influential features based on statistical metrics.

### 3. Machine Learning Models
Implemented and evaluated the following algorithms:
- **Logistic Regression**:
  - A simple and interpretable baseline model for binary classification.
- **Random Forest**:
  - A robust ensemble learning method offering feature importance insights.
- **K-Nearest Neighbors (KNN)**:
  - A non-parametric algorithm for instance-based learning.
- **Support Vector Machine (SVM)**:
  - A powerful classifier using hyperplanes for maximum margin separation.

### 4. Evaluation Metrics
- **Accuracy**: Overall correctness of the model.
- **Precision**: Proportion of true positive predictions among all positive predictions.
- **Recall**: Ability of the model to identify all positive instances.
- **F1-Score**: Harmonic mean of precision and recall.
- **ROC-AUC**: Performance comparison across different thresholds.

---

## 📈 Results

- **Best Model**: Random Forest
  - Accuracy: **96.5%**
  - Precision: **95.8%**
  - Recall: **97.2%**
  - F1-Score: **96.5%**
  - ROC-AUC: **98.1%**

### Comparative Performance of Models:
| Model                | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|----------------------|----------|-----------|--------|----------|---------|
| Logistic Regression  | 92.8%   | 91.2%     | 93.5%  | 92.3%    | 95.2%   |
| Random Forest        | 96.5%   | 95.8%     | 97.2%  | 96.5%    | 98.1%   |
| K-Nearest Neighbors  | 91.0%   | 89.6%     | 91.8%  | 90.7%    | 94.0%   |
| Support Vector Machine | 94.7%  | 93.3%     | 95.4%  | 94.3%    | 96.7%   |

---
