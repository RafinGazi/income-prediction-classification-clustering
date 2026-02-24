# Income Prediction and Clustering Analysis

## Overview

This project explores supervised and unsupervised learning techniques on a census income dataset.

The study includes:

- Data preprocessing and feature engineering
- Logistic Regression and Support Vector Machine classification
- Hyperparameter tuning using GridSearchCV
- K-Means clustering for pattern discovery
- Comparative performance evaluation

The objective was to evaluate predictive performance while analysing structural patterns within the dataset.

---

## Methodology

- Missing values were handled using categorical imputation strategies.
- Duplicate records were removed to maintain data integrity.
- Categorical features were encoded appropriately based on their structure.
- The dataset was split into training and test sets (90/10).
- Features were normalised using training-set parameters.

---

## Supervised Learning

Two classification models were implemented:

- Logistic Regression
- Support Vector Machine (SVM)

Models were evaluated using 10-fold cross-validation, followed by hyperparameter tuning using GridSearchCV.

Optimised models were then evaluated on a held-out test set to assess generalisation performance.

---

## Unsupervised Learning

K-Means clustering was applied to the normalised feature space to explore natural groupings within the data.

Cluster distributions and centroid prototypes were analysed to interpret demographic patterns.

Clustering performance was compared with supervised models to highlight differences between label-free and label-informed learning approaches.

---

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## How to Run

Install dependencies:

pip install -r requirements.txt

Then run:

jupyter notebook income_prediction_and_clustering_analysis.ipynb
