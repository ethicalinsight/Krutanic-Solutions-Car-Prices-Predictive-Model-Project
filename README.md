# Applied Data Science & Predictive Machine Learning Portfolio

A comprehensive data science repository featuring end-to-end predictive machine learning pipelines, exploratory data analysis, and feature engineering applied to automotive valuation and healthcare risk screening.

---

## 📌 Repository Overview
This portfolio highlights technical implementations across predictive modeling, data cleaning, and statistical analysis. It demonstrates the complete lifecycle of data science workflows—translating raw datasets into trained machine learning models, feature importance insights, and stakeholder-ready analytics.

### 🔍 Key Competencies Demonstrated
* **Data Transformation & Cleaning:** Preprocessed complex datasets, handled missing values, and managed outlier distributions.
* **Exploratory Data Analysis (EDA):** Identified underlying trends, correlations, and feature distributions using visual analytics.
* **Feature Engineering & Encoding:** Engineered domain-specific features and applied categorical encoding (`One-Hot Encoding`, `Label Encoding`).
* **Machine Learning Pipelines:** Built, tuned, and evaluated regression and classification models using Scikit-Learn.
* **Model Evaluation Metrics:** Evaluated models using $R^2$, MAE, and RMSE for regression, alongside Recall, ROC-AUC, and Confusion Matrices for classification.

---

# 🚗 Project 1: Used Car Resale Valuation Model

## 📌 Overview
An automotive analytics project focused on predicting used car resale values using supervised machine learning algorithms to enable data-driven pricing strategies.

## 🛠️ Tech Stack & Methods
* **Domain:** Automotive Analytics / Price Optimization
* **Tools & Libraries:** Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Algorithms Applied:** Linear Regression, Random Forest Regressor
* **Focus Areas:** Feature engineering, hyperparameter tuning, model evaluation

## 🧠 Problem Statement
Used car pricing is influenced by non-linear variables—including brand tier, mileage, fuel type, transmission, and vehicle age. Manual estimation leads to valuation inconsistencies. This pipeline automates price estimation with statistical accuracy.

## ⚙️ Methodology & Execution
1. **EDA & Trend Analysis:** Analyzed depreciation rates against vehicle age, mileage thresholds, and brand categories.
2. **Feature Engineering & Encoding:** Applied categorical encoding and feature scaling to structure raw vehicle specs for linear and non-linear tree models.
3. **Model Training & Evaluation:** Trained baseline linear regression and ensemble Random Forest models, optimizing parameters using $R^2$, MAE, and RMSE evaluation metrics.

## 📊 Key Results & Insights
* **Model Performance:** Random Forest Regressor outperformed baseline linear models, achieving strong predictive precision across price tiers.
* **Primary Price Drivers:** Identified mileage, vehicle age, and brand category as the highest-ranked feature importance factors.

---

# 🫁 Project 2: Clinical Lung Cancer Risk Prediction

## 📌 Overview
A healthcare analytics project applying supervised machine learning classification to assess lung cancer risk profiles based on patient clinical indicators and behavioral risk factors.

## 🛠️ Tech Stack & Methods
* **Domain:** Healthcare Analytics / Predictive Diagnostics
* **Tools & Libraries:** Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Algorithms Applied:** Random Forest Classifier, Support Vector Machines (SVM)
* **Model Accuracy:** ~92%
* **Focus Areas:** Feature interpretability, recall optimization, ethical modeling

## 🧠 Problem Statement
Early detection of lung cancer significantly improves patient outcomes. This project leverages accessible medical and behavioral indicators to classify high-risk profiles, supporting proactive risk screening frameworks.

## ⚙️ Methodology & Execution
1. **Clinical Risk Factor EDA:** Examined correlation patterns between key symptoms, behavioral factors (e.g., smoking intensity), and demographic attributes.
2. **Feature Optimization:** Engineered composite variables for fatigue clustering and behavioral risk intensity.
3. **Model Training & Recall Optimization:** Trained Random Forest and SVM classifiers, prioritizing high **Recall** and **ROC-AUC** scores to minimize false negatives in medical screening.
4. **Ethical Framing:** Evaluated decision thresholds to prevent misclassification risks and over-reliance on limited attributes.

## 📊 Key Results & Impact
* Achieved **~92% classification accuracy** with optimized sensitivity/recall for high-risk patient indicators.
* Output structured feature importance rankings to assist non-technical stakeholders in interpreting risk factors.
