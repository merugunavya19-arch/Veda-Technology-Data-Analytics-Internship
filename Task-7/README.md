## 📊 Sales Tracker in Google Sheets
## 📌 Project Overview

This project is a **Sales Tracker created using Google Sheets** with the **Sample Superstore dataset**.

The tracker is designed to organize sales data and automatically calculate **daily, weekly, and monthly sales totals** using spreadsheet formulas.

## 🎯 Objectives
Organize sales data for easy tracking.
Calculate daily sales totals automatically.
Calculate weekly sales using date ranges.
Calculate monthly sales using date ranges.
Use SUMIFS for automated sales calculations.
Apply data validation to prevent incorrect entries.
Verify calculated totals using manual checks.
## 🛠️ Tools Used
Google Sheets
Spreadsheet Formulas
SUMIFS
Data Validation
Sample Superstore Dataset
## 📁 Dataset

The project uses the **Sample Superstore dataset**, which contains sales-related information such as:

Order Date
Product Name
Category
Region
Sales
Quantity
Discount
Profit
## 📊 Sales Tracker Structure

The workbook contains two main sections:

## 1. Raw Data

The Raw Data sheet contains the original Superstore sales records.

Important fields used for the tracker include:

**Order Date** – used as the sales date
**Product Name**– identifies the product
**Category** – identifies the product category
**Quantity** – number of units sold
**Sales** – total sales amount
## 2. Summary

The Summary sheet provides automatically calculated:

Daily Sales
Weekly Sales
Monthly Sales
## 🧮 Formula Used
## Daily Sales
=SUMIFS('Raw Data'!$R:$R,'Raw Data'!$C:$C,A5)

This calculates total sales for the date entered in the Summary sheet.

## Weekly Sales

SUMIFS with date ranges is used to calculate sales for a specific seven-day period.

## Monthly Sales

SUMIFS with date ranges is used to calculate sales for a particular month.

## 🔐 Data Validation

Data validation is applied to improve data accuracy.

## Category

Allowed categories:

Furniture
Office Supplies
Technology
## Quantity

Quantity is restricted to values greater than or equal to 1 to prevent invalid entries such as 0 or negative numbers.

## ✅ Verification

The calculated totals are checked against the original sales data to ensure that the formulas are producing accurate results.

## 📈 Key Learning Outcomes

Through this project, I improved my practical understanding of:

Google Sheets
Sales data organization
SUMIFS formulas
Date-based calculations
Data validation
Automated reporting
Basic business data analysis
## 📌 Conclusion

This project demonstrates how Google Sheets can be used to transform raw sales data into an organized sales tracking system with automated daily, weekly, and monthly calculations. It helped strengthen practical skills in spreadsheet automation, data validation, and business data analysis.

## 👩‍💻 Author

M. Navya Sri
Data Analytics Intern
Veda Technology – Internship Task
