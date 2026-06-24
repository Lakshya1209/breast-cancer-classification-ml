# breast-cancer-classification-ml
# Breast Cancer Classification using Machine Learning

## Overview

This project was developed as part of the Artificial Intelligence & Machine Learning Internship at Maincraft Technology.

The objective of this project is to build and evaluate classification models for predicting whether a breast tumor is malignant or benign using the Breast Cancer Wisconsin Dataset provided by Scikit-Learn.

The project focuses on classification model evaluation, confusion matrix interpretation, precision, recall, F1-score analysis, ROC-AUC evaluation, handling class imbalance, and model comparison.

---

## Dataset

Dataset: Breast Cancer Wisconsin Dataset

Source:
Scikit-Learn Built-in Dataset

Target Classes:

* 0 → Malignant
* 1 → Benign

Dataset Size:

* 569 Samples
* 30 Features

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn

---

## Project Workflow

### 1. Data Loading

* Loaded Breast Cancer Dataset
* Created feature matrix and target labels

### 2. Data Preprocessing

* Train-Test Split
* Feature Scaling using StandardScaler

### 3. Classification Model

* Logistic Regression

### 4. Evaluation Metrics

* Confusion Matrix
* Precision
* Recall
* F1 Score
* Accuracy
* ROC Curve
* AUC Score

### 5. Handling Class Imbalance

* Logistic Regression with class_weight='balanced'

### 6. Model Comparison

Compared:

* Logistic Regression
* Balanced Logistic Regression
* Decision Tree Classifier

---

## Results

### Logistic Regression

* Accuracy: 98%
* Precision: 98% – 99%
* Recall: 98% – 99%
* F1 Score: 98% – 99%
* AUC Score: 0.9954

### Balanced Logistic Regression

* Accuracy: 96%

### Decision Tree Classifier

* Accuracy: 91.23%

---

## Confusion Matrix

[[41 1]
[1 71]]

Interpretation:

* True Negatives = 41
* False Positives = 1
* False Negatives = 1
* True Positives = 71

---

## ROC-AUC Analysis

AUC Score = 0.9954

The ROC Curve demonstrates excellent classification performance, indicating that the model can effectively distinguish between malignant and benign tumors.

---

## Final Model Selection

Logistic Regression was selected as the final model because it achieved:

* Highest Accuracy
* Highest F1 Score
* Excellent Precision and Recall
* Outstanding ROC-AUC Score
* Strong Generalization Performance

---

## Key Learnings

* Difference between Regression and Classification
* Confusion Matrix Interpretation
* Precision vs Recall Trade-Off
* F1 Score Importance
* ROC Curve and AUC Evaluation
* Handling Imbalanced Data
* Classification Model Comparison

---

## Internship Task

Artificial Intelligence & Machine Learning Internship

Task 4:
Classification Models, Evaluation Metrics & Handling Imbalanced Data

---

## Author

Lakshya Goyal

B.Tech Artificial Intelligence & Machine Learning

Symbiosis Institute of Technology, Nagpur
