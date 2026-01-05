# 🧪 Semiconductor Yield Prediction
### Feature Selection • ML Model Comparison • Yield Classification

This project focuses on predicting **Pass/Fail yield outcomes** in a semiconductor
manufacturing process using **sensor-level process data**.

The dataset contains a large number of measured signals, many of which may be
redundant or noisy. The objective is to identify **critical features** and build
robust machine learning models to support **yield improvement and process optimization**.

---

## 🎯 Business Objective

- Predict Pass/Fail yield of semiconductor process entities
- Identify key sensor signals impacting yield
- Reduce feature dimensionality without sacrificing model performance
- Support faster process learning and cost reduction

---

## 📊 Dataset Overview

- ~1,567 production records
- ~591 sensor features
- Binary target: Pass / Fail
- High-dimensional, noisy manufacturing data

---

## 🛠️ Tools & Technologies

- **Python** (Pandas, NumPy, Scikit-learn)
- **Exploratory Data Analysis (EDA)**
- **Statistical Analysis**
- **Feature Selection & Dimensionality Reduction**
- **SMOTE for class imbalance**
- **Machine Learning Models**
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
  - Naive Bayes
- **GridSearchCV & Cross-Validation**

---

## 🔍 Methodology

1. Data exploration and understanding
2. Missing value treatment and data cleansing
3. Univariate, bivariate, and multivariate analysis
4. Feature selection and dimensionality reduction
5. Train-test split and data standardization
6. Model training, tuning, and evaluation
7. Model comparison and selection

---

## 📈 Model Evaluation

- Compared multiple supervised learning models
- Evaluated performance using:
  - Accuracy
  - Precision, Recall, F1-score
  - Classification reports
- Selected the best-performing model based on
  generalization and interpretability

---

## 🎯 Key Outcomes

- Improved understanding of critical yield-impacting features
- Reduced feature space while maintaining predictive performance
- Identified the most effective model for yield classification
- Demonstrated practical ML workflow on high-dimensional industrial data

---

## 📂 Repository Contents

- Jupyter notebook with full analysis and modeling
- Supporting documentation and reports
- Saved model artifacts (if applicable)

---

## 📫 Contact

- 📧 Email: venkateshwaran0720@gmail.com  
- 🔗 LinkedIn: https://www.linkedin.com/in/venkateshwaran-mani-a3b2b23a3  
- 🌐 Portfolio: https://venkateshwaran-0a7i.github.io/Venkateshwaran_Mani_Portfolio  

---

⭐ Feel free to explore the notebook and analysis.


## 📊 Dataset Description

The dataset used in this project represents **sensor-level measurements from a semiconductor manufacturing process**.

- **Source**: Industrial sensor and process monitoring data  
- **File**: `signal-data.csv`  
- **Observations**: ~1,567 production entities  
- **Features**: ~591 sensor and process variables  
- **Target Variable**: Binary yield outcome  
  - `-1` → Pass  
  - `1` → Fail  

Each row corresponds to a single production entity at a specific test point, and each feature represents a measured signal collected from sensors or process control systems.

---

## 🧠 Problem Context

Modern semiconductor manufacturing generates a **large number of sensor signals**, many of which may be:
- Redundant  
- Noisy  
- Weakly related to yield outcomes  

The challenge is to:
- Identify **critical signals** impacting yield  
- Reduce dimensionality without losing predictive power  
- Build robust models that generalize well  

This makes the dataset **high-dimensional, noisy, and imbalanced**, closely reflecting real-world industrial data challenges.

---

## ⚙️ Data Challenges Addressed

- High feature-to-sample ratio  
- Missing values and noisy signals  
- Class imbalance in yield outcomes  
- Multicollinearity among sensor features  

These challenges were addressed through **data cleaning, feature selection, dimensionality reduction, and model tuning**.

