# Capstone1-Insurance-Premium
# Insurance Premium Prediction

**Domain:** Insurance · Regression
**Programme:** 3MTT Data Science Cohort 3

---

## Overview

An end-to-end regression pipeline that predicts insurance
premium amounts from policyholder data. Built on a dataset
of over 200,000 records with 20 features covering
demographics, health history, and policy attributes.

---

## Problem

Manual insurance pricing is slow and inconsistent.
This model automates premium estimation using customer
data, improving pricing accuracy and reducing assessment time.

---

## Workflow

1. Loaded and explored 200,000+ record dataset
2. Handled missing values using SimpleImputer
3. Engineered Policy Age feature from date columns
4. Applied log1p transformation to skewed features
5. Scaled numerical features using StandardScaler
6. Built scikit-learn pipeline — preprocessing + model
7. Trained and compared Linear Regression, Random Forest,
   and Gradient Boosting
8. Evaluated with MAE, RMSE, and R² score

---

## Tools

Python · pandas · NumPy · scikit-learn · SciPy
Matplotlib · Seaborn · Plotly · Google Colab

---

## Dataset

200,000+ policyholder records, 20 features.
Target variable: Premium Amount (continuous)

---

## Author

Adewole Toluwalope Olumide
Agricultural Economist & Data Scientist
Lagos, Nigeria
github.com/Adewole-Toluwalope
