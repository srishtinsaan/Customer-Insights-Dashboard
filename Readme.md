# Customer Insights & Sales Analytics Dashboard

## 📌 Overview

An end-to-end retail analytics project that analyzes **541K+ online retail transactions** to identify sales trends, customer purchasing behavior, product performance, and regional sales patterns.

The project uses **Python for data cleaning and exploratory data analysis**, **Excel for business analysis**, and **Power BI for interactive visualization and dashboarding**.

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Excel
* Power BI
* GitHub

---

## 📊 Dataset

**Online Retail Dataset — UCI Machine Learning Repository**

The dataset contains transaction-level information from an online retail store between **December 2010 and December 2011**.

### Dataset Features

* `InvoiceNo` — Transaction/invoice number
* `StockCode` — Product code
* `Description` — Product description
* `Quantity` — Number of products purchased
* `InvoiceDate` — Transaction date and time
* `UnitPrice` — Price per unit
* `CustomerID` — Customer identifier
* `Country` — Customer's country



---

## 🧹 Data Cleaning

The dataset was cleaned using Python and Pandas.

Key steps included:

* Handling missing values
* Identifying duplicate records
* Identifying cancelled transactions
* Handling invalid unit prices
* Removing transactions without Customer IDs
* Converting transaction dates into datetime format
* Creating a separate dataset for cancelled transactions

---

## ⚙️ Feature Engineering

A new revenue metric was created:

```text
Revenue = Quantity × UnitPrice
```

Additional time-based features were extracted:

* Year
* Month
* Month Name
* Day Name
* Hour

---

## 🔍 Exploratory Data Analysis

The analysis covers:

* Monthly revenue trends
* Revenue by country
* Top products by revenue
* Top customers by spending
* Customer-level purchase analysis
* Quantity distribution
* Unit price distribution
* Outlier analysis
* Key business KPIs

---

## 📈 Key Business Metrics

The analysis calculates:

* Total Revenue
* Total Orders
* Total Customers
* Average Order Value
* Customer Spending
* Product Revenue
* Country-wise Revenue

---

## 📊 Power BI Dashboard

The final dashboard contains:

### KPI Cards

* Total Revenue
* Total Orders
* Total Customers
* Average Order Value

### Visualizations

* Monthly Revenue Trend
* Top 10 Products by Revenue
* Revenue by Country
* Top 10 Customers by Revenue

### Interactive Filters

* Country
* Year
* Month

---


