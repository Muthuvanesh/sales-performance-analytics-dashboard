# 📊 Sales Performance Analytics Dashboard

<div align="center">
  <img src="./sales-dashboard.png"
       alt="Sales Performance Analytics Dashboard"
       width="100%" />
</div>
## 📌 Project Overview

The **Sales Performance Analytics Dashboard** is an exploratory data analysis (EDA) project designed to analyze sales data, identify business patterns, and understand performance across product categories, regions, order statuses, and payment methods.

Using Python and data visualization libraries, this project focuses on data cleaning, data quality analysis, exploratory analysis, and clear visualizations to help transform raw sales data into meaningful business insights.

## 🎯 Objectives

- Perform exploratory data analysis (EDA).
- Inspect dataset structure, data types, and statistical summaries.
- Identify missing values and exact duplicate records.
- Clean inconsistent text values and standardize categorical columns.
- Analyze sales patterns across product categories and regions.
- Examine order statuses and customer payment preferences.
- Create simple, meaningful visualizations.
- Interpret analytical findings to support data-driven decisions.

---

## 🗂️ Dataset Information

The project uses the `sales_dataset.csv` dataset.

The dataset contains sales-related information that can be explored to understand product categories, regional distribution, order status, and payment methods.

### Features

| Feature | Description |
|---|---|
| `Order_ID` | Identifier associated with an order |
| `Product_Category` | Category of the product |
| `Region` | Geographic sales region |
| `Order_Status` | Status of the order |
| `Payment_Method` | Method used for payment |
| `Gender` | Customer gender category |

*Note: Verify these columns against your actual CSV file and add any additional sales-related fields present in your dataset.*

---

## 🛠️ Technologies Used

- **Python** — Programming and analysis
- **Pandas** — Data manipulation and cleaning
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Jupyter Notebook** — Interactive development
- **Google Colab** — Cloud-based notebook environment

---

## 🔄 Project Workflow

### 1. Data Loading and Inspection

The notebook loads the sales dataset using Pandas and examines its structure.

The initial inspection includes:

- `df.head()` — View the first five rows
- `df.shape` — Check the number of rows and columns
- `df.info()` — Inspect data types and non-null values
- `df.describe()` — Generate descriptive statistics
- `df.isnull().sum()` — Count missing values
- `df.duplicated().sum()` — Identify exact duplicate rows

### 2. Data Cleaning

The dataset is checked and cleaned to improve data quality.

The cleaning process includes:

- Identifying missing values.
- Removing exact duplicate records.
- Standardizing inconsistent text values.
- Cleaning categorical columns such as `Product_Category`, `Region`, `Order_Status`, `Payment_Method`, and `Gender`.
- Validating data types and checking data consistency.

Repeated
