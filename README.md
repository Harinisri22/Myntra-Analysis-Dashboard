# 📜 Power BI Project – Myntra Analysis Dashboard

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Data Modeling](https://img.shields.io/badge/Data%20Model-Star%20Schema-blue)
![Visualization](https://img.shields.io/badge/Visualization-Interactive%20Dashboard-green)
![Year](https://img.shields.io/badge/Years-2023%20%7C%202024%20%7C%202025-orange)

---

## 📌 Project Overview
The **Myntra Analysis Dashboard** is a Power BI project designed to analyze and visualize Myntra’s sales performance from **2023 to 2025**.  
It provides **interactive dashboards** that deliver clear insights into **sales growth, product performance, customer orders, and state-wise trends**.  

The dashboard helps in tracking KPIs and identifying patterns that support **data-driven business decisions**.

---

## 🎯 Purpose of the Project
- To analyze **year-wise and month-wise sales performance**.  
- To identify **top-performing products and brands**.  
- To evaluate **customer order trends and return rates**.  
- To visualize **sales contribution across states**.  
- To create a **data-driven dashboard** for better decision-making.

---

## 📂 Workflow
1. **Data Collection & Import**
   - Collected multiple CSV datasets such as Sales, Orders, Products, Brands, and Customers.
   - Imported data into Power BI.

2. **Data Cleaning (Power Query)**
   - Removed duplicate entries and null values.
   - Standardized column names and data types.

3. **Data Modeling**
   - Designed a **Star-like (hybrid) Schema** with `Sales` as the fact table.
   - Established **one-to-many relationships** with dimension tables (Products, Customers, Brands, States).

4. **DAX Measures Created**
   - `Total Sales = SUM(Sales[TotalSale])`  
   - `Top 5 Products Sales`  
   - `Customer Count = DISTINCTCOUNT(Customers[CustomerID])`  
   - `Return Rate % = DIVIDE(SUM(Orders[Returned]), COUNTROWS(Orders))`  
   - `Average Rating = AVERAGE(Products[Rating])` and more.

5. **Dashboard Pages**
   - **Page 1:** Myntra Sales Overview  
   - **Page 2:** Product & Order Insights  
   - **Page 3:** State-wise Performance Overview

---

## 📊 Key Insights
- **Top 5 Products** contributed the majority of total revenue.  
- **Steady growth trend** observed across 2023–2025.  
- **High-performing states** like Maharashtra, Karnataka, and Tamil Nadu showed strong sales.  
- **Customer purchase and return patterns** helped identify improvement areas.  
- Provided **brand-wise and product-wise insights** for strategic decisions.

---

## 🛠 Tools & Technologies Used
- **Tool:** Microsoft Power BI  
- **Data Cleaning & Transformation:** Power Query  
- **Data Modeling:** Star star-like Schema (Fact & Dimension Tables)  
- **DAX Functions:** SUM, CALCULATE, DIVIDE, DISTINCTCOUNT, AVERAGE  
- **Visualization Types:**  
  - Bar Chart  
  - Line Chart  
  - Pie Chart  
  - Map  
  - Cards (KPI)  
  - Slicers  
  - Tables and more.

---

## 📑 Dataset Information
- The dataset includes multiple tables such as:  
  - **Sales Table:** Order ID, Product ID, Total Sale, Quantity, Date  
  - **Orders Table:** Order ID, Customer ID, Return Status, Order Date  
  - **Products Table:** Product ID, Brand, Category, Rating, Price  
  - **Brands Table:** Brand ID, Brand Name  
  - **Customers Table:** Customer ID, Gender, Age, State  
  - **States Table:** State, Region  

- Data covers Myntra’s sales records for **2023, 2024, and 2025**.

---

## 📊 Dashboard Pages Overview
### 1️ **Myntra Sales Overview**
- **Visuals Used:** KPI Cards, Line Chart, and Column Chart  
- Displays total sales, total orders, revenue trends, and yearly comparisons.

### 2️ **Product & Order Insights**
- **Visuals Used:** Bar Chart, Pie Chart, and Table  
- Shows top-selling products, brand performance, and customer order frequency.

### 3️ **State-wise Overview**
- **Visuals Used:** Map Chart, Column Chart, and KPI Cards  
- Displays geographical sales distribution and top-performing states.

---

## 📈 Results
- Built a **fully interactive Power BI dashboard** integrating all sales data.  
- Simplified **business performance tracking** and **trend analysis**.  
- Helped in **identifying high-performing regions and products**.  
- Enhanced **data visualization and storytelling** for strategic decisions.

---

## 👩‍💻 Author
**Harinisri S**  
- 📧 Email: [harinisrioff@gmail.com](mailto:harinisrioff@gmail.com)  
- 🔗 [LinkedIn](https://www.linkedin.com/in/harinisri-s)  
- 🔗 [GitHub](https://github.com/Harinisri22)

---
