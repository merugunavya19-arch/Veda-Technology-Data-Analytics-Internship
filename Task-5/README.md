## 📊 Excel Formulas & Functions Fundamentals
## 📌 Project Overview

This project demonstrates the use of **Excel Formulas and Functions** on the **Sample Superstore dataset**.

The workbook focuses on applying commonly used Excel functions to real business data and understanding how these formulas can be used for data analysis.

## 🎯 Objectives
Practice lookup functions using **VLOOKUP** and **XLOOKUP**
Use logical functions such as **IF**
Perform conditional calculations using **SUMIFS**
Count records using **COUNTIFS**
Apply useful **Text Functions**
Test formulas with different types of data
Understand when and why each Excel function is used
## 🛠️ Tools Used
Microsoft Excel
Excel Formulas & Functions
Sample Superstore Dataset
## 📁 Dataset

The project uses the **Sample Superstore** dataset containing fields such as:

Order ID
Order Date
Ship Date
Ship Mode
Customer ID
Customer Name
Segment
Region
Category
Sub-Category
Product ID
Product Name
Sales
Quantity
Discount
Profit
## 📋 Functions Demonstrated
## 1️⃣ VLOOKUP

Used to search for a value in the first column of a table and return a related value.

Example:

=VLOOKUP(A2,'Raw Data'!G:R,7,FALSE)

This demonstrates finding the **Region** based on the Customer Name.

## 2️⃣ XLOOKUP

Used to search for a value and return the corresponding value from another column.

Example:

=XLOOKUP(A2,Lookup!A:A,Lookup!B:B,"Not Found")

This demonstrates finding the **Product Name** using the Product ID.

## 3️⃣ IF

Used to make a logical decision based on a condition.

Example:

=IF(R2>500,"High Sales","Low Sales")
## 4️⃣ SUMIFS

Used to calculate a total based on one or more conditions.

Example:

=SUMIFS('Raw Data'!R:R,'Raw Data'!O:O,"Technology")

This calculates total sales for the **Technology** category.

## 5️⃣ COUNTIFS

Used to count records that satisfy multiple conditions.

Example:

=COUNTIFS('Raw Data'!O:O,"Technology")

This counts the number of records belonging to the Technology category.

## 6️⃣ Text Functions

Text functions are used to manipulate and extract information from text data.

Examples include:

LEFT
RIGHT
MID
LEN
UPPER
LOWER
TRIM
## 📄 Workbook Structure
Excel-Formulas-and-Functions/
│
├── Raw Data
├── Lookup
├── VLOOKUP
├── XLOOKUP
├── IF
├── SUMIFS
├── COUNTIFS
└── Text Functions
## 🔍 Testing

The formulas are tested using:

Blank cells
Text values
Numeric values
Existing Superstore data
Matching and non-matching lookup values

This helps understand how Excel formulas behave with different types of input.

## 📚 Key Learning Outcomes

Through this task, I practiced:

Excel lookup functions
Conditional calculations
Logical functions
Text manipulation
Data filtering and analysis
Formula testing
Applying Excel functions to real-world business data
## 📌 Conclusion

This project demonstrates how Excel formulas and functions can be applied to the **Sample Superstore dataset** to perform lookup, calculation, counting, logical, and text-based analysis.

The task helped strengthen practical skills in Microsoft Excel, Data Analysis, Formula-Based Calculations, and Business Data Interpretation.

## 👩‍💻 Author

M. Navya Sri

Data Analytics Intern

Veda Technology – Internship Task
