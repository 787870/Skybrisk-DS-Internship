# 📂 Month 3: Machine Learning & Predictive Modeling

This folder contains the final capstone projects for my Data Science internship at **The Skybrisk**. The focus shifted from Exploratory Data Analysis to building, evaluating, and deploying predictive machine learning models to forecast customer churn.

---

## 🛠️ Weekly Task Overview

### **Week 1: Data Preprocessing & Baseline Modeling**
* **Data Preparation:** Engineered features using one-hot encoding and scaled numerical features using `StandardScaler` to ensure uniform mathematical weighting.
* **Baseline Model:** Trained an initial **Logistic Regression** classifier on the telecom dataset, achieving a strong baseline accuracy of ~79%.

### **Week 2: Advanced Evaluation Metrics**
* **Metric Analysis:** Moved beyond pure accuracy by utilizing Confusion Matrices and Classification Reports to analyze Precision, Recall, and F1-Scores for imbalanced datasets.
* **Diagnostic Visualization:** Plotted the Receiver Operating Characteristic (ROC) curve, achieving an AUC of 0.83, validating the model's strong predictive capabilities.

### **Week 3: Ensemble Modeling & Feature Importance**
* **Algorithm Upgrade:** Implemented a **Random Forest Classifier** with balanced class weights to penalize minority class misclassifications and capture hidden churners.
* **Business Drivers:** Extracted and visualized Feature Importance, proving mathematically that `TotalCharges`, `Tenure`, and `Month-to-month contracts` are the primary drivers of customer turnover.

### **Week 4: Model Deployment & Inference**
* **Live System:** Developed a scalable Python inference function that accepts raw customer profiles, applies training-level scaling transformations, and outputs a clear probability score and risk classification for stakeholder use.

---

## 📈 Key Learning Outcomes
* Transitioning from descriptive analytics to **Predictive Machine Learning** using `scikit-learn`.
* Evaluating model performance using industry-standard metrics (ROC-AUC, Precision/Recall).
* Translating complex AI models into deployable, business-friendly inference functions.
