# CSE422: Artificial Intelligence — Adult Income Prediction

A machine learning project for **CSE422: Artificial Intelligence**, focused on predicting whether an individual's annual income is **≤50K or >50K** using the Adult Income dataset.

The project explores data analysis, preprocessing, feature engineering, supervised learning, and unsupervised learning through multiple machine learning models.

---

## 📌 Project Overview

The main objective of this project is to develop and evaluate machine learning models that can predict an individual's income class based on demographic, educational, occupational, and financial attributes.

The project covers:

- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature engineering
- Train-test splitting
- Supervised learning
- Neural Networks
- Decision Trees
- Logistic Regression
- Unsupervised learning with K-Means clustering
- Model evaluation and comparison

### Target Variable

The target variable is:

- `<=50K` — Income is less than or equal to 50K
- `>50K` — Income is greater than 50K

This makes the primary task a **binary classification problem**.

---

## 📊 Dataset

The project uses the **Adult Income dataset**, which contains demographic, educational, employment, and financial information about individuals.

### Main Features

- Age
- Workclass
- Education
- Education Number of Years
- Marital Status
- Occupation
- Relationship
- Race
- Sex
- Capital Gain
- Capital Loss
- Hours per Week
- Native Country
- Final Weight

### Target

`target`

---

## 🤖 Machine Learning Models

### Supervised Learning

The following classification models are implemented:

- **Logistic Regression**
- **Decision Tree**
- **Neural Network**

These models are trained to predict whether an individual's income falls into the `<=50K` or `>50K` class.

### Unsupervised Learning

- **K-Means Clustering**

K-Means is used to explore whether meaningful groups can be identified within the dataset without using the income target during clustering.

---

## 🔍 Project Workflow

```text
Dataset
   ↓
Exploratory Data Analysis
   ↓
Data Preprocessing
   ↓
Feature Engineering
   ↓
Train-Test Split
   ↓
Model Training
   ├── Logistic Regression
   ├── Decision Tree
   └── Neural Network
   ↓
Model Evaluation & Comparison

Dataset without Target
   ↓
K-Means Clustering
   ↓
Cluster Analysis

```
---

## 👥 Team Contributions

| Team Member | EDA | Preprocessing | Feature Engineering | Train-Test Split | Logistic Regression | Decision Tree | Neural Network | K-Means |
|---|---|---|---|---|---|---|---|---|
| **Najah** | ✅ | ✅ | — | — | ✅ | ✅ | — | — |
| **Rayhan** | — | — | ✅ | ✅ | — | — | ✅ | ✅ |
