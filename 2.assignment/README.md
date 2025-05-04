# IN3050 – Assignment 2 (2025)

This repository contains the second mandatory assignment for the course **IN3050 – Introduction to Artificial Intelligence and Machine Learning** at the University of Oslo.

## 📚 Assignment Overview

The assignment explores **supervised learning** techniques using both binary and multi-class classification. The goal is to build and evaluate linear models, logistic regression models, and multi-layer neural networks (MLPs) from scratch on synthetic datasets, using a scientific and experimental approach.

## 🧪 What’s Implemented

### ✅ Binary Classification
- **Linear Regression Classifier** (with MSE loss)
- **Logistic Regression Classifier** with:
  - Probabilistic output
  - Loss tracking (cross-entropy)
  - Accuracy tracking
  - Early stopping
- **Multi-layer Perceptron (MLP)** with:
  - One hidden layer
  - Probabilities and predictions
  - Loss/accuracy tracking
  - Early stopping and tuning

### ✅ Multi-class Classification
- **One-vs-Rest Logistic Regression** approach
- Visualization of decision boundaries
- Per-class accuracy analysis

### ✅ Evaluation
- Comparison across training, validation, and test sets
- Accuracy, precision, and recall scores
- Visual plots of performance and training dynamics

## 📊 Results Summary

| Model               | Train Accuracy | Validation Accuracy | Test Accuracy |
|--------------------|----------------|----------------------|---------------|
| Linear Regression   | 0.755          | 0.758                | 0.754         |
| Logistic Regression | 0.777          | 0.771                | 0.765         |
| MLP (Best)          | 0.779          | 0.787                | 0.771         |

Precision and recall (class 1, test set):
- **Linear Regression**: Precision = 0.749, Recall = 0.612  
- **Logistic Regression**: Precision = 0.888, Recall = 0.496  
- **MLP**: Precision = 0.860, Recall = 0.535  

## 📈 Visuals
The assignment includes:
- Decision region plots
- Loss and accuracy curves per epoch
- Comparative tables with tuning metrics

## 🔧 Requirements
- Python 3.12
- `numpy`, `matplotlib`, `pandas`, `sklearn`

To run the code, install dependencies and execute the main scripts in Jupyter Notebook or Python script format.

## 👤 Author
**Dmitrii Soltaganov**  
Email: [dmitriis@uio.no](mailto:dmitriis@uio.no)  
Course: IN3050 – Spring 2025

---

This project was completed as part of a mandatory assignment and is intended for educational purposes only.
