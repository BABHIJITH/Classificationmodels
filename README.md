# Classification models
# Breast Cancer Classification - Exploratory Data Analysis & Model Comparison

## 📌 Overview
This repository contains an extensive **Exploratory Data Analysis (EDA)** and model performance comparison on a **Breast Cancer Classification dataset**. We analyze the dataset, visualize patterns, and evaluate multiple machine learning models to determine the best-performing classifier.

---

## 🔍 Exploratory Data Analysis (EDA)
We begin by exploring the dataset to understand feature distributions, correlations, and patterns.

### 📊 Plots Generated:
- **Distribution of Diagnosis** (Benign vs. Malignant)
- **Feature Histograms** to visualize value distributions
- **Correlation Heatmap** to identify feature relationships
- **Box Plots** for key features
- **Pair Plot** to analyze feature interactions

---

## 🚀 Machine Learning Models Used
We trained multiple classification models to predict breast cancer diagnosis:

1️⃣ **Random Forest**  
2️⃣ **Naïve Bayes**  
3️⃣ **K-Nearest Neighbors (KNN)**  
4️⃣ **Support Vector Machine (SVM)**  
5️⃣ **Logistic Regression**

Each model was trained, tested, and evaluated using **accuracy, precision, recall, and F1-score**.

---

## 📈 Model Performance Comparison

| Model                | Accuracy | Precision | Recall | F1-Score |
|----------------------|----------|------------|---------|----------|
| Random Forest       | 96.49%    | 97.56%     | 93.02%  | 95.24%   |
| Naïve Bayes        | 97.37%    | 100%       | 93.02%  | 96.39%   |
| KNN                | 95.61%    | 100%       | 88.37%  | 93.83%   |
| SVM                | 94.74%    | 100%       | 86.05%  | 92.50%   |
| Logistic Regression | 95.61%    | 97.50%     | 90.70%  | 93.98%   |

🏆 **Best Performing Model: Naïve Bayes**  
Based on accuracy and precision, **Naïve Bayes** demonstrated the best performance, achieving **97.37% accuracy** and **100% precision**.  

---


## 📌 Acknowledgments
- Data sourced from the **Breast Cancer Diagnostic dataset**.
- **Libraries Used**: `pandas`, `matplotlib`, `seaborn`, `sklearn`

