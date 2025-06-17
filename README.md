# Telecom Customer Churn Prediction

This repository contains an end-to-end machine learning project focused on predicting customer churn in the telecom sector. It involves data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation using **Logistic Regression**.

---

## Project Objective

The goal of this project is to analyze customer behavior and predict the likelihood of a customer **churning** (i.e., leaving the telecom service provider). Identifying such customers in advance helps businesses take proactive retention measures.

---

## Workflow Overview

### 1. Data Loading and Inspection
- Loaded the dataset from a `.csv` file using `pandas`
- Displayed data structure, summary statistics, and missing values

### 2. Exploratory Data Analysis (EDA)
- Histograms to understand feature distributions
- Pair plots grouped by churn status
- Correlation matrix and heatmap of numerical features

### 3. Data Preprocessing
- Handled missing values with mean imputation
- Performed one-hot encoding for categorical variables
- Feature scaling using `StandardScaler`

### 4. Model Training
- Used **Logistic Regression** to train on the processed data
- Split the data using `train_test_split` (80/20 ratio)

### 5. Model Evaluation
- Evaluated model using:
  - **Classification Report** (Precision, Recall, F1-score)
  - **Confusion Matrix**
  - **ROC Curve & AUC Score**

---

## Key Visualizations

- Histograms for each feature
- Pair plot colored by churn status
- Heatmap of feature correlations
- Confusion Matrix
- ROC Curve with AUC score

---

## Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

---

