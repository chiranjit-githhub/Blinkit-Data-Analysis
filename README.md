# 🛒 Blinkit Data Analysis using Python, Excel & MySQL

## 📖 Project Overview

This project analyzes Blinkit grocery sales data to uncover valuable business insights related to sales performance, customer purchasing behavior, product categories, and revenue trends. The analysis was performed using **Python** for data cleaning and exploration, **MySQL** for querying and business analysis, and **Microsoft Excel** for creating an interactive dashboard.

The objective of this project is to transform raw transactional data into meaningful insights that support data-driven business decisions.

---

## 🎯 Objectives

- Analyze overall sales performance.
- Identify top-performing product categories and products.
- Understand customer purchasing behavior.
- Analyze sales trends over time.
- Evaluate payment method preferences.
- Create an interactive dashboard for business reporting.

---

## 🛠️ Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  - Matplotlib
- **MySQL**
- **Microsoft Excel**
  - Pivot Tables
  - Pivot Charts
  - Slicers
  - Conditional Formatting

---

## 📂 Project Structure

```
Blinkit-Data-Analysis/
│
├── Data/
│   └── blinkit_sales.csv
│
├── SQL/
│   └── Blinkit_SQL_Queries.sql
│
├── Python/
│   └── blinkit_analysis.ipynb
│
├── Dashboard/
│   └── Blinkit_Dashboard.xlsx
│
├── Images/
│   ├── dashboard.png
│   ├── sales_by_category.png
│   ├── monthly_sales.png
│   └── top_products.png
│
└── README.md
```

---

## 📊 Dataset Information

The dataset contains Blinkit grocery sales transactions with the following attributes:

- Order ID
- Product Name
- Category
- Quantity
- Unit Price
- Total Sales
- Customer Rating
- Payment Method
- Order Date
- Delivery Location

---

## 🔄 Project Workflow

### 1. Data Collection

- Imported the Blinkit sales dataset.

### 2. Data Cleaning (Python)

Performed the following preprocessing steps:

- Removed duplicate records
- Handled missing values
- Corrected data types
- Formatted date columns
- Checked inconsistent values
- Prepared data for SQL analysis

### 3. SQL Analysis

Imported the cleaned dataset into MySQL and performed analytical queries such as:

- Total Revenue
- Total Orders
- Average Order Value
- Top Selling Products
- Category-wise Sales
- Monthly Sales Trend
- Payment Method Analysis
- Customer Rating Analysis

### Example SQL Query

```sql
SELECT Category,
SUM(Total_Sales) AS Revenue
FROM blinkit_sales
GROUP BY Category
ORDER BY Revenue DESC;
```

### 4. Dashboard Creation (Excel)

Developed an interactive Excel dashboard using:

- Pivot Tables
- Pivot Charts
- KPI Cards
- Slicers
- Conditional Formatting

---

## 📈 Key Performance Indicators (KPIs)

- Total Revenue
- Total Orders
- Average Order Value
- Average Customer Rating
- Total Products Sold
- Monthly Sales Growth
- Best Selling Category

---

## 📊 Dashboard Features

The dashboard includes visualizations for:

- Sales by Product Category
- Monthly Revenue Trend
- Top Selling Products
- Payment Method Distribution
- Customer Rating Distribution
- Revenue Comparison
- Order Trends

---

## 💡 Key Insights

- Identified the highest revenue-generating product categories.
- Determined the best-selling products based on sales volume.
- Analyzed monthly sales trends to identify peak business periods.
- Compared payment methods to understand customer preferences.
- Evaluated customer ratings across different product categories.
- Generated actionable insights for inventory planning and sales strategy.

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- SQL Query Writing
- Database Management
- Data Visualization
- Dashboard Development
- Business Intelligence
- Business Insight Generation

---

## 📸 Dashboard Preview
<img width="1918" height="1031" alt="image" src="https://github.com/user-attachments/assets/2f5c5dd2-bd82-4515-bdc4-a2c4db02ec88" />

## 📚 What I Learned

Through this project, I gained practical experience in:

- Cleaning and preparing real-world sales data.
- Writing SQL queries for business analysis.
- Creating interactive dashboards in Excel.
- Generating business insights from transactional data.
- Presenting findings using effective visualizations.

---

## 🔮 Future Enhancements

- Develop a Power BI dashboard.
- Build a Tableau dashboard.
- Perform customer segmentation analysis.
- Implement sales forecasting using Machine Learning.
- Create an interactive Streamlit web application.

---

## 👨‍💻 Author

**Chiranjit Sahu**

Aspiring Data Analyst

### Technical Skills

- Python
- SQL
- MySQL
- Microsoft Excel
- Power BI
- Tableau
- Data Analysis
- Data Visualization

---

## ⭐ Support

If you found this project useful, please consider **starring** this repository on GitHub.

---

## 📌 Repository Structure

```
Blinkit-Data-Analysis/
│
├── Data/
│   └── blinkit_sales.csv
│
├── SQL/
│   └── Blinkit_SQL_Queries.sql
│
├── Python/
│   └── blinkit_analysis.ipynb
│
├── Dashboard/
│   └── Blinkit_Dashboard.xlsx
│
├── Images/
│   ├── dashboard.png
│   ├── sales_by_category.png
│   ├── monthly_sales.png
│   └── top_products.png
│
├── LICENSE
└── README.md
```
