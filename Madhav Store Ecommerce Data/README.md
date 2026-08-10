# 📊 E-Commerce Sales Analysis Dashboard

An interactive **Power BI dashboard** designed to analyze e-commerce sales performance, profitability, product categories, customer sales, payment methods, and regional performance.

The project demonstrates the complete data analytics workflow — from importing and transforming raw data to creating interactive visualizations and extracting business insights.

---

## 📌 Project Overview

The objective of this project is to build an interactive business intelligence dashboard that helps understand:

- Overall sales performance
- Total profit and quantity
- Average Order Value (AOV)
- Monthly profit trends
- State-wise sales performance
- Category-wise quantity distribution
- Payment mode preferences
- Sub-category profitability
- Customer-wise sales performance

The dashboard allows users to interact with the data using **Quarter and State filters**.

---

## 🎯 Objectives

- Analyze overall e-commerce sales performance.
- Identify profitable and high-performing product categories.
- Understand customer purchasing patterns.
- Compare sales performance across different states.
- Analyze monthly profit trends.
- Understand customer payment preferences.
- Build an interactive and easy-to-use business dashboard.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI** | Dashboard development and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Measures and KPI calculations |
| **CSV** | Source data |
| **Data Visualization** | Business insights and reporting |

---

## 📂 Dataset

The project uses two CSV datasets:

### `Details.csv`

Contains transaction-level information:

- Order ID
- Amount
- Profit
- Quantity
- Category
- Sub-Category
- Payment Mode

### `Orders.csv`

Contains order and customer information:

- Order ID
- Order Date
- Customer Name
- State
- City

The datasets are connected using **Order ID**.

---

## 🔄 Data Analysis Workflow

```text
Raw CSV Data
      ↓
Data Import
      ↓
Data Cleaning & Transformation
      ↓
Data Modeling
      ↓
DAX Measures
      ↓
Interactive Visualizations
      ↓
Power BI Dashboard
      ↓
Business Insights
