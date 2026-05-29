# 📊 Customer Analytics Report | SQL Data Analytics Project

## 🚀 Project Overview

This project focuses on transforming raw customer and sales data into meaningful business insights using SQL. The objective is to build a customer-centric analytics solution that helps businesses understand customer behavior, identify high-value customers, and make data-driven decisions.

The project combines customer and sales datasets to create a comprehensive customer report that can be leveraged for business intelligence dashboards and strategic analysis.

---

## 🎯 Business Problem

Businesses generate large volumes of transactional data, but extracting actionable insights from that data can be challenging.

This project answers key business questions such as:

✅ Who are the most valuable customers?

✅ Which customers qualify as VIPs?

✅ How recently have customers made purchases?

✅ What is the average spending behavior of customers?

✅ Which age groups contribute the most revenue?

✅ How long do customers remain active?

---

## 🗂️ Dataset

### 👥 Customers Table

Contains customer demographic information.

**Fields**

* Customer Key
* First Name
* Last Name
* Birth Date
* Gender

### 🛒 Sales Table

Contains transactional sales records.

**Fields**

* Order Number
* Product Key
* Customer Key
* Order Date
* Sales Amount
* Quantity

### 📦 Products Table

Contains product-related information.

**Fields**

* Product Key
* Product Name
* Category
* Subcategory

---

## 🔄 Project Workflow

### 1️⃣ Data Extraction

* Retrieved customer and sales data from source tables.
* Joined datasets using Customer Key.

### 2️⃣ Data Transformation

* Calculated customer age.
* Cleaned and standardized customer information.
* Prepared customer-level reporting data.

### 3️⃣ Customer Aggregation

Generated customer-level metrics:

📌 Total Orders

📌 Total Sales

📌 Total Quantity Purchased

📌 Total Products Purchased

📌 First Purchase Date

📌 Last Purchase Date

📌 Customer Lifespan

### 4️⃣ KPI Development

Developed business KPIs:

📈 Recency

📈 Average Order Value (AOV)

📈 Average Monthly Spend

### 5️⃣ Customer Segmentation

Classified customers into business-friendly segments.

| Segment   | Criteria                                  |
| --------- | ----------------------------------------- |
| 🏆 VIP    | Lifespan ≥ 12 Months & Total Sales > 5000 |
| ⭐ Regular | Lifespan ≥ 12 Months & Total Sales ≤ 5000 |
| 🆕 New    | Lifespan < 12 Months                      |

---

## 📌 Key Metrics

### ⏳ Recency

Measures the number of months since a customer's most recent purchase.

### 🔄 Lifespan

Measures the duration between the first and last customer purchase.

### 💰 Average Order Value (AOV)

Average revenue generated per customer order.

### 📊 Average Monthly Spend

Average customer spending per active month.

---

## 👨‍👩‍👧‍👦 Age Group Classification

| Age Range | Group           |
| --------- | --------------- |
| Below 20  | 🧒 Under 20     |
| 20 – 29   | 👨 20-29        |
| 30 – 39   | 👨‍💼 30-39     |
| 40 – 49   | 👔 40-49        |
| 50+       | 👴 50 and Above |

---

## 🛠️ SQL Concepts Used

✔️ Common Table Expressions (CTEs)

✔️ Joins

✔️ Aggregations

✔️ CASE Statements

✔️ Date Functions

✔️ Customer Segmentation

✔️ KPI Calculations

✔️ View Creation

✔️ Business Reporting

---

## 📋 Final Customer Report

The final report includes:

* 👤 Customer Name
* 🎂 Age Group
* 🏷️ Customer Segment
* 📦 Total Orders
* 💵 Total Sales
* 🛒 Total Quantity Purchased
* 📦 Total Products Purchased
* ⏳ Recency
* 🔄 Lifespan
* 💰 Average Order Value
* 📈 Average Monthly Spend

---

## 📊 Dashboard Design

The report is designed to support an interactive business intelligence dashboard.

### 📍 Executive Summary

* 👥 Total Customers
* 💰 Total Sales
* 📦 Total Orders
* 💵 Average Order Value
* 📈 Average Monthly Spend
* 🏆 VIP Customers

### 📍 Customer Analysis

* 🍩 Customer Segment Distribution
* 📊 Revenue by Segment
* 👨‍👩‍👧‍👦 Age Group Analysis
* ⏳ Recency Analysis
* 🔄 Customer Lifespan Analysis

### 📍 Customer Insights

* 🏅 Top Customers by Revenue
* 📋 Detailed Customer Report
* 🎛️ Interactive Filters

---

## 🧠 Skills Demonstrated

### 💻 Technical Skills

* SQL Querying
* Data Cleaning
* Data Transformation
* Data Aggregation
* Data Modeling
* Business Reporting

### 📈 Analytics Skills

* Customer Segmentation
* KPI Development
* Customer Behavior Analysis
* Revenue Analysis
* Retention Analysis

### 🏢 Business Skills

* Customer Lifetime Analysis
* Customer Value Identification
* Data-Driven Decision Making
* Business Intelligence Reporting

---

## 🔧 Tools & Technologies

| Tool                           | Purpose                     |
| ------------------------------ | --------------------------- |
| 🐬 MySQL                       | Data Storage & Analysis     |
| 🐙 GitHub                      | Version Control & Portfolio |
| 📝 SQL Workbench               | Query Development           |
| 📊 Power BI (Dashboard Design) | Reporting & Visualization   |

---

## 📈 Project Outcome

✅ Developed a customer analytics reporting solution using SQL.

✅ Created customer-level KPIs and business metrics.

✅ Implemented customer segmentation for business insights.

✅ Designed a dashboard framework for executive reporting.

✅ Enabled data-driven decision-making through actionable customer insights.

---
