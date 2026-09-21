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
