# 📊 Sales Performance Analytics Dashboard

<div align="center">
  <img src="./sales-dashboard.png" alt="Sales Performance Analytics Dashboard" width="100%" />
</div>

## 📌 Project Overview

This project focuses on performing exploratory data analysis (EDA) on a sales dataset to understand data quality, product categories, regional distribution, order statuses, and customer payment preferences.

The notebook performs end-to-end data inspection, data cleaning, categorical data standardization, exploratory analysis, and visualization using Python data analysis libraries.

The goal is to transform raw sales data into meaningful insights through simple, clear, and informative visualizations.

---

## 🎯 Objectives

- Perform exploratory data analysis (EDA).
- Inspect dataset structure, data types, and statistical summaries.
- Identify missing values and duplicate records.
- Clean inconsistent and improperly formatted categorical values.
- Analyze product category and regional distributions.
- Examine order status and payment method patterns.
- Create meaningful visualizations using Matplotlib and Seaborn.
- Interpret data patterns to support data-driven business decisions.

---

## 🗂️ Dataset Information

The project uses the `sales_dataset.csv` dataset.

The dataset contains sales-related records that can be analyzed to understand product categories, regional distribution, order statuses, and customer payment preferences.

### Features

| Feature | Description |
|---|---|
| `Order_ID` | Identifier associated with an order |
| `Product_Category` | Category of the product |
| `Region` | Geographic sales region |
| `Order_Status` | Status of the order |
| `Payment_Method` | Payment method used |
| `Gender` | Customer gender category |

*Note: Verify the feature names against the actual CSV file. Include any additional columns present in your dataset.*

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab

---

## 🔄 Project Workflow

### 1. Data Loading and Inspection

The notebook loads the sales dataset using Pandas and examines its structure and contents.

The initial inspection includes:

- `df.head()` — Display the first five rows.
- `df.shape` — Check the number of rows and columns.
- `df.info()` — Inspect data types and non-null values.
- `df.describe()` — Generate descriptive statistics.
- `df.isnull().sum()` — Identify missing values.
- `df.duplicated().sum()` — Count exact duplicate rows.

### 2. Data Cleaning

The dataset is cleaned to improve data quality and consistency.

The cleaning process includes:

- Identifying missing values.
- Removing exact duplicate records.
- Standardizing text values.
- Cleaning categorical columns such as `Product_Category`, `Region`, `Order_Status`, `Payment_Method`, and `Gender`.
- Checking data types and validating column values.

Repeated `Order_ID` values are not automatically removed because a single order may contain multiple product records.

### 3. Exploratory Data Analysis (EDA)

EDA is performed to understand the characteristics and patterns of the dataset.

The analysis focuses on:

- Product category distribution.
- Regional distribution.
- Order status distribution.
- Payment method preferences.
- Customer category distribution.
- Comparisons between relevant categorical variables.

### 4. Data Visualization

Matplotlib and Seaborn are used to create clear visualizations that make patterns easier to understand.

The charts help compare categories, examine distributions, and communicate important observations.

The notebook uses `plt.show()` to display visualizations directly rather than saving each chart as a PNG file.

### 5. Insights and Interpretation

The results are interpreted to identify patterns in the available data.

The analysis can help answer questions such as:

- Which product categories appear most frequently?
- How are records distributed across regions?
- Which order statuses are most common?
- Which payment methods are used most frequently?
- What patterns can be observed in the dataset?

Actual conclusions are based on the results produced by the notebook.

---

## 📊 Visualizations

The project uses simple visualizations to explore and present the dataset.

### 1. Product Category Distribution

A count plot can compare the number of records across product categories and identify the most frequently occurring categories.

### 2. Regional Distribution

A bar chart can display the distribution of records across regions and make regional comparisons easier.

### 3. Order Status Distribution

A count plot can show the frequency of different order statuses and help summarize the order status distribution.

### 4. Payment Method Distribution

A bar chart can compare payment methods and highlight the most frequently used options.

*The charts described above should match the visualizations actually implemented in the notebook.*

---

## 💡 Key Learnings

This project demonstrates practical experience in:

- Loading and inspecting structured datasets.
- Identifying missing values and duplicate records.
- Cleaning and standardizing categorical data.
- Using Pandas for data manipulation and analysis.
- Performing exploratory data analysis.
- Creating visualizations with Matplotlib and Seaborn.
- Interpreting patterns in sales-related data.
- Presenting analytical findings in a clear and understandable way.

---

## 🚀 Installation and Execution

### 1. Clone the repository

Replace `your-username` with your GitHub username.

```bash
git clone https://github.com/your-username/sales-performance-analytics-dashboard.git
```

### 2. Open the project folder

```bash
cd sales-performance-analytics-dashboard
```

### 3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the notebook

Open `sales_performance_analytics_dashboard.ipynb` and execute the cells in order.

Ensure that `sales_dataset.csv` and `sales-dashboard.png` are available in the project folder. The CSV path used in the notebook must match the dataset's actual location.

Alternatively, upload the notebook and dataset to Google Colab and run the analysis there.

---

## 📁 Project Structure

```text
sales-performance-analytics-dashboard/
│
├── sales_performance_analytics_dashboard.ipynb
├── sales_dataset.csv
├── sales-dashboard.png
├── README.md
└── requirements.txt
```

---

## 🔮 Future Improvements

- Build an interactive dashboard using Streamlit or Power BI.
- Add filters for product categories and regions.
- Analyze revenue and profit if the required numerical columns are available.
- Explore sales trends over time if the dataset contains date information.
- Develop additional business performance metrics.
- Deploy an interactive dashboard for users to explore sales data.

---

## 📘 Conclusion

The Sales Performance Analytics Dashboard demonstrates how exploratory data analysis can be used to inspect, clean, visualize, and interpret structured sales data.

The project provides a foundation for more advanced analytics, business reporting, and interactive dashboard development.

---

## 👨‍💻 Author

**Muthu Vanesh**

GitHub: [Muthuvanesh](https://github.com/Muthuvanesh)

---

## 📌 Disclaimer

This project is intended for educational and portfolio demonstration purposes. The observations and conclusions depend on the actual dataset, its quality, and the analyses performed.
