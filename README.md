# EcommerceSalesDataAnalysis
Analyzed e commerce data using sql in python by importing pandasql 
# 🛒 E-Commerce Data Analysis Project

This project explores and analyzes an e-commerce dataset using Python and SQL within a Google Colab environment. The goal is to extract key business insights that can help understand sales performance, customer behavior, and product trends.

---

## 📌 Objectives

- Clean and format raw e-commerce data
- Perform SQL-based analysis using `pandasql`
- Extract top insights such as:
  - Total revenue
  - Top 10 customers by spend
  - Top 10 best-selling products

---

## 📂 Dataset Info

The dataset includes columns such as:

- `InvoiceNo` – Invoice number of the transaction
- `StockCode` – Unique product code
- `Description` – Product description
- `Quantity` – Units sold
- `UnitPrice` – Price per unit (originally a float)
- `CustomerID` – Unique customer ID
- `InvoiceDate` – Date of purchase
- `Country` – Customer country

---

## 🔧 Data Cleaning & Formatting

- **Formatted `UnitPrice`** with currency symbol (`$`) into a new column `UnitPriceFormatted`
- **Dropped original `UnitPrice`** column after formatting
- Checked for `NULL` values in `InvoiceNo` and handled them
- Calculated a `TotalPrice` column = `Quantity × UnitPrice`

---

## 📊 Key Insights

### ✅ Total Revenue

- Calculated total revenue by summing `Quantity × UnitPrice`
- **Total Revenue: `$9,747,748`**

### 👥 Top 10 Customers by Spend

| CustomerID | Total Spend ($) |
|------------|------------------|
| ...        | ...              |

*(See full results in notebook)*

### 📦 Top 10 Products by Quantity Sold

| Product Description | Quantity Sold |
|---------------------|----------------|
| ...                 | ...            |

---

## 🧪 Tech Stack

- Python (Pandas, Pandasql)
- Google Colab
- SQL for analysis (`pandasql`)

---

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Upload the dataset (`.csv`)
3. Run through the steps: cleaning → SQL analysis → visualization
4. Download final results or publish on GitHub

---

## 📁 Output

- Cleaned and formatted dataset
- Analysis notebook (`.ipynb`)
- This `README.md`

---

## 📬 Author

**Kanishka Rana**  
_Data Enthusiast • Python & SQL Learner_

---


