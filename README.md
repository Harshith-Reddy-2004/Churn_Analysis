# Telecom Customer Churn Analysis & Prediction

This project demonstrates an **end-to-end churn analysis** workflow for a telecom company, from data extraction to actionable insights. It combines **SQL Server ETL**, **Power BI dashboards**, and a **Random Forest machine learning model in Python** to identify at-risk customers and the key factors behind churn.

---

## 📊 Project Overview

Customer churn analysis helps telecom providers **understand and reduce customer attrition**. By analyzing historical customer data, we can:

* Detect patterns and reasons for customer departures.
* Predict which customers are likely to leave.
* Implement proactive strategies to improve retention.

This project covers:

1. **Data Engineering:** ETL pipeline in SQL Server to clean, transform, and load telecom data.
2. **Data Visualization:** Interactive Power BI dashboards for demographic, geographic, and service-usage analysis.
3. **Machine Learning:** Random Forest classifier in Python to predict churn and highlight key drivers.

---

## 🏗️ Tech Stack

| Layer              | Technology                                                    |
| ------------------ | ------------------------------------------------------------- |
| Data Storage/ETL   | **SQL Server**                                                |
| Data Visualization | **Power BI**                                                  |
| Machine Learning   | **Python (scikit-learn, pandas, numpy, matplotlib, seaborn)** |


## ⚙️ Implementation Steps

### 1️⃣ Data Extraction & Transformation (SQL Server)

* Imported raw telecom data.
* Cleaned missing values, standardized formats, and created derived features (e.g., tenure groups, service categories).

### 2️⃣ Exploratory Data Analysis

* Identified churn patterns by demographics, location, contract type, and service usage.
* Visualized churn distributions and correlations.

### 3️⃣ Power BI Dashboard

* Built interactive dashboards to track:

  * **Demographics**: Age, gender, region
  * **Service Usage**: Internet plans, contract types
  * **Geographic Patterns**: Churn hotspots

### 4️⃣ Machine Learning Model

* Trained a **Random Forest classifier** to predict churn probability.
* Evaluated using Accuracy, Precision, Recall.
* Extracted feature importances to reveal key churn drivers.

## 🏁 Results & Insights

* Identified **high-risk customer segments** by contract type, tenure, and service bundle.
* Provided data-driven recommendations for **retention campaigns**.

---

## 📈 Future Enhancements

* Integrate real-time scoring API for live churn prediction.
* Experiment with Gradient Boosting or XGBoost models.
* Automate Power BI data refresh with Azure Data Factory.

---

## 🧑‍💻 Author

**Harshith Reddy**
Feel free to connect or raise issues for collaboration and improvements.
