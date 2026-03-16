
# Fraud Detection - Exploratory Data Analysis

## 1. Dataset Overview

- Total Rows: 283726
- Total Columns: 32

## 2. Class Distribution

Fraud vs Non-Fraud:

Class
0    99.83329
1     0.16671

Observation:

The dataset is **highly imbalanced**, which is expected in fraud detection problems.

## 3. Data Cleaning

- Duplicate transactions removed: 1081

Data cleaning ensures that duplicated operations do not bias the model.

## 4. Statistical Analysis

Two statistical tests were applied to compare fraud and non-fraud transaction distributions.

### Kolmogorov-Smirnov Test

p-value: 7.446283420073041e-30

This test checks if the two samples come from the same distribution.

### Mann-Whitney U Test

p-value: 2.68609023836721e-05

This non-parametric test evaluates whether one distribution tends to have larger values than the other.

## 5. Key Insights

- Fraud transactions show statistical differences compared to normal transactions
- The dataset is extremely imbalanced
- Feature distributions suggest potential predictive signals

## 6. Next Steps

- Feature Engineering
- Handling class imbalance
- Model training and evaluation

---

Report automatically generated from the EDA notebook.
