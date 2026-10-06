## 📊 Simple KPI Tracking Sheet – Superstore Dataset
## 📌 Overview

This project focuses on creating a **Simple KPI Tracking Sheet using Microsoft Excel** and the **Sample Superstore dataset**.

The objective is to convert raw transactional data into a **business-ready one-page KPI summary** that provides a quick view of important sales performance indicators.

## 🎯 Objectives
Convert raw sales data into meaningful business KPIs.
Create a simple one-page KPI summary.
Use Excel formulas for automatic calculations.
Present key business metrics in a clear and professional format.
Practice analyzing transactional data for business reporting.
## 📊 KPIs Tracked

The KPI summary includes four key metrics:

**KPI**	                   **Description**
**Revenue**	                Total sales generated from all transactions
**Units Sold**              Total quantity of products sold
**Average Order Value**	    Average sales value per order
**Top Product**	            Product with the highest total sales
## 🗂️ Dataset

The project uses the **Sample Superstore dataset**.

Important columns used:

Order ID
Product Name
Sales
Quantity
## Column Mapping
**KPI**	                        **Dataset Column**
Revenue	                        Sales
Units Sold	                    Quantity
Average Order Value	            Order ID + Sales
Top Product	                    Product Name + Sales
## 🧮 Excel Formulas Used
## Revenue
=SUM(RawData!R:R)

Calculates the total revenue from the Sales column.

## Units Sold
=SUM(RawData!S:S)

Calculates the total quantity of products sold.

## Average Order Value
=SUM(RawData!R:R)/COUNTA(RawData!B:B)

Calculates the average sales value based on the Order ID records.

## Top Product

A **PivotTable** was used to identify the product with the highest total sales.

**Rows**: Product Name
**Values**: Sum of Sales
**Sorting**: Largest to Smallest by Sum of Sales
## 📋 KPI Results

The completed KPI summary contains:

**Revenue**: ₹22,97,200.86
**Units Sold**: 37,873
**Average Order Value**: ₹229.84
**Top Product**: Canon imageCLASS 2200 Advanced Copier
## 🛠️ Tools Used
Microsoft Excel
Sample Superstore Dataset
Excel Formulas
PivotTables
Data Analysis
KPI Reporting
## 📁 Project Structure
Simple-KPI-Tracking/
│
├── RawData
├── KPI Summary
├── PivotTable
└── README.md
## 📈 Key Features
One-page KPI summary
Automated KPI calculations using Excel formulas
Revenue and units tracking
Average Order Value calculation
Top Product identification using PivotTable
Currency formatting for financial KPIs
Professional and easy-to-read layout
## 🎓 Learning Outcomes

Through this task, I gained practical experience in:

KPI identification and tracking
Excel formulas
PivotTable analysis
Business data summarization
Sales performance analysis
Creating business-ready reports
## ✅ Conclusion

This project demonstrates how raw transactional data can be transformed into a simple and effective KPI tracking sheet. The dashboard provides a quick overview of revenue, units sold, average order value, and the top-performing product, helping translate raw data into meaningful business information.

## 👩‍💻 Author

M. Navya Sri
Data Analytics Intern – Veda Technology
