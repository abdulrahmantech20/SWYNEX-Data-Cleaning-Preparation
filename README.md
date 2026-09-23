# FMCG Sales Data Cleaning & Preparation

## 📌 Overview

This project focuses on **data cleaning, validation, and feature engineering** for an FMCG sales dataset using Python. The objective was to transform raw transactional data into a structured, consistent, and analysis-ready dataset for downstream business analytics and visualization.

## 🛠️ Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Jupyter Notebook**

## 🔍 Data Preparation

The dataset contains **50,750 records and 15 attributes** covering orders, customers/companies, locations, products, pricing, payments, discounts, GST, and delivery information.

Key data preparation activities included:

* Dataset profiling and structural validation
* Missing-value identification and treatment
* Duplicate record detection and removal
* Date standardization and conversion
* Categorical data normalization
* Numeric type conversion and validation
* Product-level median imputation for missing unit prices
* Correction of negative quantity values
* Handling missing payment methods
* Identification and correction of abnormal delivery-day values
* Range and anomaly validation

## 📊 Feature Engineering

The following business metrics were created from the cleaned transactional data:

* **Gross Amount**
* **Discount Amount**
* **Net Sales (INR)**

These calculated fields prepare the dataset for further sales analysis and reporting.

## 📁 Output

The cleaned dataset is exported as:

`cleaned_Fmcg_Sales.csv`

## 🎯 Project Outcome

The final output is a **clean, standardized, and analysis-ready FMCG sales dataset** that can be used as a foundation for further **SQL analysis, Excel reporting, and Power BI dashboard development**.

---

**Project Focus:** Data Cleaning • Data Quality • Feature Engineering • Business Analytics

## Exploratory Data Analysis — Python

After cleaning the dataset, I performed exploratory data analysis using Python to understand sales performance, identify trends and patterns, and find unusual sales records.

### Analysis Performed

* Checked dataset structure and data quality
* Calculated descriptive statistics
* Calculated key business KPIs
* Analyzed sales by product category
* Analyzed sales by state
* Analyzed sales by store type
* Analyzed sales by city tier
* Analyzed monthly sales trends
* Examined high-value sales records
* Checked the relationship between discounts and net sales

### Key KPIs

* **Total Orders:** 50,000
* **Total Net Sales:** Approximately ₹160.87 million
* **Average Order Value:** Approximately ₹3,217
* **Total Quantity Sold:** Calculated from the cleaned dataset

### Key Insights

1. Dairy & Staples is one of the largest contributors to total sales.
2. Sales vary significantly across states.
3. Kirana Stores generate the highest sales among the store types.
4. Tier 1 cities generate the highest sales compared with Tier 2 and Tier 3 cities.
5. Monthly sales vary throughout the analysis period.
6. Some orders have unusually high sales values and require further investigation.
7. The relationship between discount percentage and net sales is weakly negative.

### Python Tools Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

### Notebook

The complete Python EDA is available here:

`python/FMCG_Sales_EDA.ipynb`

