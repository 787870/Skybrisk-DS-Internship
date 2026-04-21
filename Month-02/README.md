# 📂 Month 2: Exploratory Data Analysis & Feature Engineering

This folder contains the projects for the second month of my Data Science internship at **The Skybrisk**. The focus shifted from basic Python manipulation to handling real-world data issues, engineering new features, and extracting business insights through Exploratory Data Analysis (EDA).

---

## 🛠️ Weekly Task Overview

### **Week 1: Data Understanding & Cleaning (Telecom Churn)**
* **Data Preparation:** Addressed missing values and converted string-based monetary columns (`TotalCharges`) into numeric types for mathematical operations.
* **Feature Engineering:** Engineered derived metrics such as `TenureGroup` to segment customers and calculated `AvgMonthlySpend`. Formatted binary variables (Yes/No to 1/0) for analysis.

### **Week 2: EDA & Visualization (Telecom Churn)**
* **Visual Analysis:** Developed countplots, boxplots, and correlation heatmaps using **Seaborn** and **Matplotlib**.
* **Business Insights:** Identified that month-to-month contracts and high monthly charges are the primary indicators of customer churn risk, while longer tenure strongly correlates with retention.

### **Week 3: Media Data Preparation (Netflix Trends)**
* **Data Parsing:** Parsed unstructured date strings into Python `datetime` objects and handled missing metadata for directors and cast members.
* **Feature Extraction:** Extracted the `release_year`, calculated the `release_decade`, and cleaned multi-label country data to identify the primary production regions.

### **Week 4: Trend Visualization & Prediction (Netflix Trends)**
* **Dashboard Creation:** Built multi-plot visual grids to map the exponential growth of content post-2014 and the historical volume dominance of Movies over TV Shows.
* **Future Prediction:** Utilized historical release trends to predict a faster growth rate for TV Shows compared to Movies over the next two years to align with modern subscription retention strategies.

---

## 📈 Key Learning Outcomes
* Advanced data cleaning techniques using **Pandas** to handle edge cases and incorrect data types.
* Creating complex, professional-grade visual dashboards using **Matplotlib** and **Seaborn**.
* Translating raw data visualizations into actionable business predictions.
