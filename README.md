# Credit Risk Scoring for Underbanked Populations

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-RandomForest-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📊 Project Overview

This project develops a **machine learning-based credit risk scoring system** for underbanked populations, where traditional credit history is limited or unavailable.

The model classifies borrowers into:

* 🟢 **Good (Low Risk)**
* 🔴 **Bad (High Risk)**

It supports **fair, data-driven lending decisions** and improves financial inclusion.


## 🚨 Problem Statement

Financial institutions struggle to assess creditworthiness due to limited financial history, leading to:

* Increased loan default risk
* Inefficient lending decisions
* Reduced access to credit for underbanked individuals

### 🎯 Objective

Build a classification model to predict loan default risk and improve credit decision-making reliability.

## 📁 Dataset Overview

The dataset includes borrower demographic, financial, and behavioral attributes.

### Key Feature Categories

* 👤 Demographics: Age group, employment type
* 💰 Financial data: Income, loan amount, bank type
* 📉 Behavioral history: Repayment pattern, previous defaults

## ⚙️ Methodology

### 1. Data Preprocessing

* Missing value handling
* Categorical encoding
* Feature scaling

### 2. Exploratory Data Analysis (EDA)

* Class distribution analysis
* Risk factor correlations
* Identification of key drivers of default

### 3. Model Building

* Algorithm: **Random Forest Classifier**
* Train-test split evaluation
* Baseline model development

### 4. Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC

## 📈 Model Performance

### 🔹 Baseline Model

* **ROC-AUC Score:** 0.5905
* Weak separation between good and bad loans

📉 Indicates limited predictive power in baseline setup.

## ⚖️ Handling Class Imbalance (SMOTE)

To improve minority class learning, **SMOTE (Synthetic Minority Oversampling Technique)** was applied.

### Improvements:

* Better detection of default (bad loan) cases
* Reduced bias toward majority class
* More balanced evaluation metrics

## 🔍 Key Risk Drivers Identified

* Previous default history
* Employment type
* Bank type
* Age group
* Borrower segmentation patterns

## 📊 Visual Insights

### Class Distribution

*(<img width="580" height="453" alt="download" src="https://github.com/user-attachments/assets/007d788e-c451-44c1-9c92-ce1987cb0724" />


# Example placeholder:
# ![Class Distribution](images/class_distribution.png)


### Feature Importance (Random Forest)

# ![Feature Importance](images/feature_importance.png)
<img width="563" height="453" alt="download" src="https://github.com/user-attachments/assets/5109afb9-56fd-494c-90cf-1c950b76c237" />
<img width="589" height="453" alt="download" src="https://github.com/user-attachments/assets/56fae9da-40c1-409c-9bb9-7b8ebfb65de9" />



## ⚠️ Challenges

* Severe class imbalance
* Limited feature richness for credit behavior
* Baseline model not tuned for optimization


## 🚀 Future Improvements

* Advanced feature engineering (Debt-to-Income Ratio, credit utilization)
* Model tuning (XGBoost, LightGBM, tuned Random Forest)
* Improved resampling strategies (SMOTE variants, class weighting)
* Threshold optimization based on business cost of default

## 🧠 Key Takeaways

* Demonstrates real-world **credit risk modeling** application
* Highlights impact of **class imbalance on model performance**
* Shows effectiveness of **SMOTE in improving minority class prediction**
* Establishes foundation for **fair and data-driven lending systems**


## 📌 Tech Stack

* Python 🐍
* Pandas & NumPy
* Scikit-learn
* Matplotlib & Seaborn
* Imbalanced-learn (SMOTE)


## 📎 Conclusion

This project presents a baseline credit risk model for underbanked populations. While initial performance was limited, SMOTE significantly improved predictive balance and fairness.

It emphasizes the importance of:
* Handling imbalanced datasets
* Feature engineering in financial ML
* Ensemble methods for classification problems


⭐ If you found this project useful, feel free to star the repo!
