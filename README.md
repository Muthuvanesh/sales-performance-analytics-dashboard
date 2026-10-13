# Online Retail Sales Analysis — Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a synthetic online retail sales dataset containing 3,000 records and 10 original columns. The goal is to clean the data, analyze sales performance, identify transaction patterns, and generate meaningful business insights through data visualization.

## 🎯 Objectives

- Understand the dataset structure and data quality.
- Identify and handle missing values and duplicate records.
- Clean inconsistent product categories, country names, prices, and dates.
- Analyze revenue by product category.
- Identify peak transaction hours and days.
- Find the top 10 products by sales volume and revenue.
- Present findings through clear, informative visualizations.

## 📂 Dataset Information

**Dataset:** `Dataset.csv`

The dataset is synthetically generated for learning and portfolio purposes.

| Column | Description |
|---|---|
| `InvoiceNo` | Invoice or transaction identifier |
| `StockCode` | Product stock identifier |
| `Description` | Product description |
| `Category` | Product category |
| `Quantity` | Quantity purchased or returned |
| `InvoiceDate` | Date and time of transaction |
| `UnitPrice` | Price per unit |
| `CustomerID` | Customer identifier |
| `Country` | Customer's country |
| `TotalPrice` | Total line-item price |

## 🛠️ Technologies Used

- **Python** — Data analysis and programming
- **Pandas** — Data manipulation and cleaning
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical charts
- **Jupyter Notebook / Google Colab** — Development environment

## 🧹 Data Cleaning and Preparation

The following steps were performed:

1. Examined dataset dimensions and the first few records.
2. Identified missing values in each column.
3. Detected and removed 74 exact duplicate rows.
4. Standardized product category labels and country names.
5. Cleaned unit prices by removing currency text and invalid values.
6. Converted quantities to numeric values and flagged extreme quantities.
7. Parsed mixed date formats and handled invalid dates.
8. Recalculated `TotalPrice` using quantity multiplied by unit price.
9. Created time-based features and identified cancellations or returns.

After removing duplicate rows, the dataset contained **2,926 records**. Further filtering may reduce the number of records used in individual analyses.

## 📊 Exploratory Data Analysis

### 1. Revenue by Product Category

- Aggregated sales revenue by product category.
- Compared category-level revenue using a horizontal bar chart.
- Used value labels to make comparisons easier.

### 2. Transaction Analysis by Hour and Day

- Analyzed transaction counts across the 24 hours of the day.
- Compared transaction activity across weekdays.
- Visualized hourly trends with a line chart and daily trends with a bar chart.

### 3. Top 10 Products by Sales Volume and Revenue

- Identified the 10 products with the highest total quantities sold.
- Identified the 10 products with the highest total revenue.
- Compared product performance using horizontal bar charts.

## 💡 Key Business Questions

This project explores the following questions:

- Which product categories generate the highest revenue?
- During which hours are transactions most frequent?
- Which days of the week have the highest transaction activity?
- Which products sell in the largest quantities?
- Which products generate the highest revenue?

The answers should be documented after validating the final charts and aggregated results.

## 📁 Project Structure

```text
online-retail-sales-eda/
│
├── messy_online_retail_3000.csv
├── online_retail_sales_eda.ipynb
└── README.md
```

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter openpyxl
   ```

3. Place `messy_online_retail_3000.csv` in the project directory.
4. Open the notebook:

   ```bash
   jupyter notebook
   ```

5. Run the notebook cells in sequence to perform data cleaning, analysis, and visualization.

You can also upload the notebook and CSV file to Google Colab and run the project there.

## 📈 Expected Outcomes

- A better understanding of data cleaning and preprocessing.
- Practical experience with exploratory data analysis.
- Visual comparisons of product category revenue and product performance.
- Insights into hourly and weekly transaction patterns.
- A reproducible Python project suitable for a beginner data analytics portfolio.

## ⚠️ Important Notes

- The dataset is synthetic and is intended for educational and portfolio purposes.
- Currency conversion must use one consistent, documented exchange rate.
- Negative quantities and cancellation invoices should be handled separately when calculating sales performance.
- Missing customer IDs may limit customer-level analysis.
- Revenue findings depend on the data-cleaning and filtering rules applied.

## 👨‍💻 Author

**Muthu Vanesh**

GitHub: [Muthuvanesh](https://github.com/Muthuvanesh)

LinkedIn: [MuthuVanesh](https://www.linkedin.com/in/MuthuVanesh)

---

⭐ If you find this project useful, consider starring the repository.
