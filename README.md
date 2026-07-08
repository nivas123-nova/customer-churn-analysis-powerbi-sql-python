# 📊 Customer Churn Analysis & Prediction Dashboard

An end-to-end analytics project that combines **SQL**, **Power BI**, and **Python (Machine Learning)** to analyze customer churn behavior, surface key business drivers of attrition, and predict which customers are likely to churn next — enabling proactive retention strategies.

---

## 🎯 Business Objective

- Analyze customer behavior and churn patterns
- Identify the key business factors contributing to customer attrition
- Develop an interactive dashboard to support data-driven decision-making
- Build a predictive model capable of identifying customers likely to churn

---

## 🧱 Project Workflow

### 1. Data Extraction & Database Management
Imported the telecom customer dataset into **Microsoft SQL Server**. Used SQL for:
- Database and table creation
- Data validation
- Exploratory SQL queries
- Filtering and aggregations
- Data extraction for reporting

**Tools:** SQL Server, SQL Server Management Studio (SSMS)

![SQL Data Exploration](images/sql_data_exploration.jpg)

### 2. Data Cleaning & Transformation
Used **Power Query** to transform raw data into an analytics-ready format:
- Handling missing values
- Removing duplicate records
- Correcting inconsistent data types
- Creating conditional columns
- Feature engineering
- Standardizing categorical variables

![Power Query Transformation](images/power_query_transformation.jpg)

### 3. Data Modeling
Designed an optimized data model in Power BI with relationships between tables, following dimensional modeling best practices for performance and scalability.

### 4. BI Dashboard Development
Built an interactive Power BI dashboard with executive-level KPIs:

| KPI | KPI |
|---|---|
| Total Customers | Total Revenue |
| Active Customers | Monthly Revenue |
| Churned Customers | Avg. Monthly Charges |
| Customer Churn Rate | Avg. Customer Tenure |

**Dashboard covers:**
- Customer Demographics
- Contract Type Analysis
- Payment Method Analysis
- Internet Service Analysis
- Customer Tenure
- Revenue Distribution
- Geographic Customer Distribution
- Customer Segmentation
- Churn by Multiple Business Dimensions

**Visuals used:** KPI cards, clustered & stacked bar charts, donut/pie charts, line charts, matrix tables, interactive slicers, drill-through navigation, dynamic filtering, conditional formatting.

![Churn Analysis Dashboard](images/dashboard_summary.jpg)

### 5. Advanced Analytics with DAX
Developed DAX measures and calculated columns for:
- Customer Churn Rate (%)
- Revenue Metrics
- Average Monthly Charges / Tenure
- Custom Business KPIs & dynamic measures

### 6. Predictive Analytics (Python)
Built a machine learning pipeline to predict customer churn:
- Data preprocessing & feature encoding
- Feature selection
- Train-test split
- Model training & prediction
- Performance evaluation

**Algorithm:** Random Forest Classifier
**Evaluation metrics:** Accuracy, Precision, Recall, F1 Score, Confusion Matrix

![ML Prediction Results](images/ml_prediction_results.jpg)

Prediction results were integrated back into Power BI, allowing stakeholders to view historical churn alongside customers with a high probability of future churn.

---

## 🛠️ Tech Stack

**Database:** Microsoft SQL Server, SSMS
**Business Intelligence:** Power BI, Power Query, DAX
**Programming:** Python (Jupyter Notebook)
**Python Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
**Data Prep:** Microsoft Excel

---

## 📊 Key Business Outcomes

- Identified customer segments with the highest probability of churn
- Quantified how contract type, tenure, payment method, and internet service impact retention
- Delivered a real-time interactive dashboard for monitoring customer behavior and business performance
- Built a predictive model to support proactive, data-driven retention strategies

---

## 📁 Repository Structure

```
├── data/                # Raw and cleaned datasets
├── sql/                 # SQL scripts (DB setup, queries, validation)
├── powerbi/              # Power BI (.pbix) dashboard file
├── notebooks/             # Jupyter notebooks (ML pipeline)
├── images/                # Dashboard screenshots
└── README.md
```

---

## 🚀 Core Skills Applied

SQL Development · Data Cleaning · ETL · Data Modeling · Data Visualization · Dashboard Development · DAX · Power Query · Exploratory Data Analysis · Machine Learning · Predictive Analytics · KPI Design · Customer Segmentation · Business Analysis

---

## 🙌 Feedback & Connect

Open to feedback from the data community — feel free to connect or raise an issue if you have suggestions for improving this project!

`#DataAnalytics` `#PowerBI` `#SQL` `#Python` `#MachineLearning` `#BusinessIntelligence` `#PredictiveAnalytics` `#CustomerChurn`
