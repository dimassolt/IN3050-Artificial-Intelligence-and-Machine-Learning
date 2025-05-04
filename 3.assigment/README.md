# IN3050 – Assignment 3 (2025)

This repository contains my solution to **Assignment 3** for the course **IN3050 – Introduction to Artificial Intelligence and Machine Learning** at the University of Oslo.

## 📚 Overview

This assignment focuses on **unsupervised learning**, specifically:

- **Principal Component Analysis (PCA)** from scratch
- **K-means clustering** using `scikit-learn`
- PCA for **visualization** and **compression**
- Evaluation of K-means clustering using a **logistic regression classifier**

## 📌 Structure

### Part 1: Principal Component Analysis (PCA)
- ✅ Implemented PCA from scratch using NumPy
- ✅ Centering data, computing covariance matrix, eigen decomposition
- ✅ Visualized projections and compared class separability before/after PCA
- ✅ Applied PCA for dimensionality reduction on:
  - Synthetic data
  - Iris dataset (visualization)
  - LFW face dataset (compression)

### Part 2: K-Means Clustering
- ✅ Applied K-means to the Iris dataset with various `k` values
- ✅ Visualized cluster assignments vs. true labels using PCA projection
- ✅ Evaluated clustering quality using a logistic regression classifier
- ✅ Plotted model accuracy across different `k` values

## 📊 Results Summary

- PCA revealed class structure effectively when variance correlated with class separability.
- LFW compression results improved visually with increasing number of principal components.
- K-means clustering achieved best performance when `k=3`, aligning with the three Iris classes.
- Logistic regression accuracy peaked at `k=3`, confirming clustering quality.

## 🔧 Requirements

Make sure you have the following installed:

```bash
pip install numpy matplotlib scikit-learn
