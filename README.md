# Deception Detection Notebooks

This repository contains a collection of Jupyter Notebooks related to the analysis, modeling, and evaluation of deception detection using machine learning techniques. Each notebook serves a distinct purpose in the overall pipeline — from data exploration to final model loading.

## Notebooks Overview

### 1. EDA.ipynb
*Purpose:*  
Performs *Exploratory Data Analysis* on the dataset to uncover patterns, distributions, and insights about deceptive and truthful instances.

*Includes:*
- Label distribution visualizations  
- Token/word frequency analysis  
- Sentence length and position-based trends  
- Initial feature hypotheses

---

### 2. AccuracyBaselineModels.ipynb
*Purpose:*  
Establishes *baseline models* for deception detection using standard classifiers and evaluates their performance.

*Includes:*
- Logistic Regression, SVM, and Naive Bayes baselines  
- Cross-validation and confusion matrices  
- Accuracy, Precision, Recall, and F1-Score comparison

---

### 3. RGDAT (1).ipynb
*Purpose:*  
Implements and tests the *RGDAT model* (Relational Graph-based Deception Attention Transformer or similar), combining advanced architectures such as BERT, BiLSTM, and GCN.

*Includes:*
- Custom model architecture  
- Integration of graph features  
- Attention mechanism visualization  
- Evaluation against baseline metrics

---

### 4. loadingmodel.ipynb
*Purpose:*  
Handles *model loading and inference*, particularly useful for deploying trained models or testing on unseen data.

*Includes:*
- Loading pre-trained models  
- Running inference on test samples  
- Output interpretation and visualization

---

## How to Run

1. Clone the repository

