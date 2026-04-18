# Advanced Power BI Sales Analysis Dashboard (Online Retail Dataset)

---

## Student Information
- Student Name: Halima Mohammed  
- Admission Number:670315  
- Course Code: DSA3050A  
- Class: BUSINESS INTELLIGENCE AND DATA VISUALIZATION

---

## Project Overview
This project presents an interactive Power BI dashboard built using the Online Retail dataset. The main objective is to analyze sales performance, customer behavior, and product trends to support data-driven decision-making. The dashboard transforms raw transactional data into meaningful insights through data modeling, DAX calculations, and visual analytics.

---

## Problem Statement
Organizations often struggle to extract meaningful insights from large volumes of raw sales data. This project addresses this challenge by designing a structured Power BI solution that enables analysis of sales trends, customer distribution, and product performance for better business decision-making.

---

## Dataset Description
The dataset used is the Online Retail dataset , which contains transactional sales records. It includes the following fields:
- InvoiceNo (transaction identifier)  
- StockCode (product identifier)  
- Description (product name)  
- Quantity (units sold)  
- InvoiceDate (transaction date and time)  
- UnitPrice (price per unit)  
- CustomerID (unique customer identifier)  
- Country (customer location)  
Dataset link: https://archive.ics.uci.edu/dataset/352/online-retail
---

## Tools Used
- Power BI Desktop for dashboard development  
- Power Query for data cleaning and transformation  
- DAX (Data Analysis Expressions) for calculations  
- Microsoft Excel for initial data inspection  

---

## Steps Followed
- Imported raw dataset into Power BI  
- Cleaned data by handling missing values and duplicates  
- Transformed data using Power Query  
- Created dimension tables (Customer, Product, Date)  
- Built a star schema data model  
- Developed calculated columns and DAX measures  
- Designed interactive dashboards with multiple report pages  

---

## Dashboard Features
- KPI cards for key business metrics such as sales, customers, and orders  
- Time-based analysis using line charts for sales trends  
- Product and category performance comparison using bar charts  
- Drill-down and decomposition tree for detailed analysis  
- Interactive slicers for filtering by country, year, and month  
- Geographic visualization using map charts  
- Top and bottom product performance analysis  

---

## Key DAX Measures
- Total Sales  
- Total Quantity Sold  
- Total Orders  
- Distinct Customers  
- Average Sales Value  
- Year-to-Date (YTD) Sales  
- Previous Year Sales  
- Sales Growth Percentage  

---

## Key Insights
- Sales performance shows fluctuations over time rather than steady growth  
- A small number of products generate a large proportion of total revenue  
- Sales distribution is uneven across different countries  
- A small group of customers contributes significantly to total revenue  
- Certain product categories consistently underperform  

---

## Challenges Encountered
- Handling missing and inconsistent data values  
- Resolving relationship issues in the data model  
- Fixing many-to-many relationship errors in Power BI  
- Designing a proper Date table for time intelligence analysis  
- Ensuring performance optimization for interactive visuals  

---

## Conclusion
The project successfully demonstrates how raw transactional data can be transformed into meaningful business insights using Power BI. The dashboard provides an interactive and structured view of sales performance, customer behavior, and product trends, supporting effective decision-making.
