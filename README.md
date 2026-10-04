# Unsupervised Learning & Model Evaluation

## 📌 Project Overview

This project demonstrates important Machine Learning concepts covering **Unsupervised Learning, Dimensionality Reduction, Classification, Model Evaluation, Cross-Validation, and Hyperparameter Tuning**.

The project explores clustering techniques such as **K-Means and Hierarchical Clustering**, uses **PCA for dimensionality reduction**, and evaluates a Logistic Regression classification model using multiple performance metrics.

The complete project was developed and executed using **Google Colab** with Python and Scikit-learn.

---

## 🎯 Objectives

* Understand Unsupervised Learning concepts.
* Implement K-Means Clustering.
* Determine the optimal number of clusters using the Elbow Method.
* Evaluate clustering quality using Silhouette Score.
* Implement Hierarchical Clustering.
* Visualize hierarchical relationships using a Dendrogram.
* Apply PCA for dimensionality reduction.
* Train a Logistic Regression classification model.
* Evaluate model performance using multiple metrics.
* Perform 5-Fold Cross-Validation.
* Perform hyperparameter tuning using GridSearchCV.
* Compare model performance before and after tuning.

---

## 🧠 Machine Learning Techniques

### 1. K-Means Clustering

K-Means is an unsupervised learning algorithm that divides data into a predefined number of clusters.

The **Elbow Method** was used to identify a suitable number of clusters.

### 2. Silhouette Score

Silhouette Score was used to measure how well-separated the clusters are.

A higher score generally indicates better-defined clusters.

### 3. Hierarchical Clustering

Agglomerative Hierarchical Clustering was implemented using Ward linkage.

A **dendrogram** was generated to visualize the hierarchical relationships between observations.

### 4. Principal Component Analysis

PCA was used for dimensionality reduction and visualization of the dataset using principal components.

### 5. Logistic Regression

Logistic Regression was used as the supervised classification model for the model evaluation section.

---

## 📊 Model Evaluation

The classification model was evaluated using:

* Confusion Matrix
* Precision
* Recall
* F1-Score
* ROC-AUC
* ROC Curve
* Classification Report

These metrics provide different perspectives on model performance rather than relying only on accuracy.

---

## 🔄 Cross-Validation

A **5-Fold Stratified Cross-Validation** approach was used to obtain a more reliable estimate of model performance.

The mean cross-validation accuracy and standard deviation were calculated.

---

## ⚙️ Hyperparameter Tuning

**GridSearchCV** was used to find suitable Logistic Regression hyperparameters.

The parameters explored included:

* `C`
* `solver`

The tuned model was then evaluated on unseen test data and compared with the original model.

---

## 🗂️ Project Structure

```text
Unsupervised-Learning-Model-Evaluation/
│
├
```
