# 📊 Retail Sales Performance Dashboard (Power BI)

## 🔎 Overview

This is a **Retail Sales Performance Dashboard** built in **Power BI** to analyze overall business performance using sales data. The dashboard focuses on **sales, cost, profit, margin, quantity, customers, products, regions, and monthly trends**.

---

## 📌 Key KPIs

* **Net Sales:** 787K
* **Total Cost:** 726K
* **Gross Profit:** 61K
* **Gross Margin %:** 91%
* **Total Quantity:** 23

---

## 📈 Dashboard Visuals

### 1️⃣ Customer Sales, Profit & Quantity (Matrix)

* Created using **Matrix visual**
* Customer → Product level breakdown
* Measures used:

  * Net Sales
  * Gross Profit
  * Total Quantity
* Includes **Total row** for summary

### 2️⃣ Monthly Net Sales Trend (Line Chart)

* Month-wise net sales analysis
* Helps identify growth and decline patterns

### 3️⃣ Gross Profit by Product (Bar Chart)

* Product-wise profit comparison
* Helps identify **high-margin products**

### 4️⃣ Net Sales by Region (Bar Chart)

* Region-wise sales comparison
* Identifies strong and weak regions

---

## 🧠 DAX Measures Used

```DAX
Net Sales = SUM(Fact_Sales[Sales_Amount])
Total Cost = SUM(Fact_Sales[Total_Cost])
Gross Profit = [Net Sales] - [Total Cost]
Gross Margin % = DIVIDE([Gross Profit], [Net Sales], 0)
Total Qty = SUM(Fact_Sales[Quantity])
```

---

## 🗂 Data Model

* Fact Table: Sales
* Dimension Tables: Date, Product, Customer, Region
* **Star Schema** used for clean modeling and performance

---

## 🛠 Tools & Skills

* Power BI Desktop
* DAX (SUM, DIVIDE)
* Data Modeling (Star Schema)
* Dashboard Design

---

## 📌 Conclusion

This project shows my ability to build **business-ready Power BI dashboards**, write **DAX measures**, and present insights clearly. Suitable for **Data Analyst / Power BI Developer (Fresher)** roles.

---

### 👤 Author

**Arif Shaikh**

