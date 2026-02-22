# 📊 Social Media Advertising Analysis

## 📌 Project Overview

This project analyzes a large-scale social media advertising dataset (300,000 campaigns) to uncover the key drivers of campaign performance, ROI, and cost efficiency.

Using advanced data preprocessing, clustering, classification, and regression modeling, the project identifies high-performing campaign strategies, evaluates budget effectiveness, and builds predictive frameworks for optimization.

---

## 🎯 Objectives

* Identify the **highest ROI channel and campaign strategy**
* Discover characteristics of **elite high-performing campaigns**
* Analyze **budget vs. conversion rate sensitivity**
* Predict **campaign success (≥10% conversion rate)**
* Build a **cost optimization regression model**
* Evaluate **ROI predictability using feature selection**

---

## 📂 Dataset

* **Source:** Kaggle – Social Media Advertising Dataset
* **Records:** 300,000 campaigns
* **Features:** 16 campaign attributes
* **Key Metrics:**

  * ROI
  * Conversion Rate
  * Acquisition Cost
  * Clicks & Impressions
  * Engagement Score

---

## 🛠️ Tools & Technologies

* Python 3.x
* Pandas & NumPy
* Scikit-learn
* XGBoost
* Matplotlib & Seaborn
* SciPy

---

## 🔎 Methodology

### 1️⃣ Data Preprocessing

* Currency and percentage normalization
* Outlier capping (99th percentile)
* Missing value handling
* Feature engineering (CTR, CPC, CPI, Engagement Score)
* One-Hot Encoding & Scaling

### 2️⃣ Exploratory Data Analysis

* Distribution analysis
* Correlation heatmaps
* Channel & audience benchmarking
* ROI relationship analysis

### 3️⃣ Clustering – Elite Campaign Identification

* K-Means clustering
* Composite scoring (ROI, Conversion Rate, Engagement Score)
* Quantile-based elite campaign extraction
* Chi-square & Cramér’s V validation

### 4️⃣ Predictive Modeling

**Classification (Campaign Success Prediction)**

* Logistic Regression
* Random Forest
* XGBoost
* ROC-AUC, PR-AUC evaluation

**Regression (Cost Optimization)**

* Linear Regression
* Ridge Regression
* Gradient Boosting Regressor
* RFECV for feature selection

---

## 📈 Key Findings

### ✅ Highest ROI

* Twitter & Instagram outperform other channels
* Product Launch and Sales campaigns yield strongest returns
* Fashion and Health segments show consistent high ROI

### 💰 Budget Sensitivity

* Increasing budget does **not significantly improve conversion rates**
* Diminishing returns observed beyond moderate spending levels

### 🏆 Elite Campaign Blueprint

* Quantile-based clustering approach provides most robust elite identification
* High ROI is driven by cost efficiency and engagement metrics

### 🤖 Predictive Modeling

* Campaign success prediction performed close to random
* Indicates missing behavioral or creative-level features

### 📊 Cost Prediction

* Gradient Boosting achieved very high R² (up to 0.998)
* Duration and Impressions are strongest cost drivers

---

## 📁 Repository Structure

```
├── Social_Media_Advertising.csv
├── Social_media_analysis_code.ipynb
├── Social Media Advertising Analysis.docx
└── README.md
```

---

## 🚀 Business Impact

* Enables data-driven campaign strategy selection
* Improves marketing budget allocation
* Identifies replicable high-performance campaign blueprints
* Provides regression-based cost planning support

---

## 📌 Future Improvements

* Incorporate creative-level and behavioral features
* Add time-series analysis
* Experiment with advanced ensemble and deep learning models
* Deploy as a dashboard or decision-support tool

---

## 🔗 References

* Kaggle Dataset: [https://www.kaggle.com/datasets/jsonk11/social-media-advertising-dataset](https://www.kaggle.com/datasets/jsonk11/social-media-advertising-dataset)
* Scikit-learn Documentation: [https://scikit-learn.org](https://scikit-learn.org)

---

