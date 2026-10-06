## Missing Value Identification – Titanic Dataset
## 📌 Project Overview

This project focuses on identifying and summarizing missing values in the **Titanic dataset** using **Microsoft Excel** and **Python with Pandas**.

The objective is to understand which columns contain missing data, calculate the number and percentage of missing values, and prepare a short summary of the findings.

## 🎯 Objective
Identify missing values in the dataset.
Count missing values for each column.
Calculate the total number of records.
Calculate the percentage of missing values.
Identify the columns that require further attention.
Summarize the findings without modifying the original dataset.
## 🛠️ Tools Used
Microsoft Excel
Google Colab
Python
Pandas
## 📂 Dataset

**Dataset**: Titanic Dataset

The dataset contains:

**891 records**
**10 columns**
## Columns
PassengerId
Survived
Pclass
Name
Sex
Age
SibSp
Parch
Ticket
Fare
## 🔍 Missing Value Analysis

The analysis showed that only the Age column contains missing values.

**Column**	          **Missing Values**	  **Total Values**	  **Missing Percentage**
PassengerId	             0	                 891	                0%
Survived	               0	                 891	                0%
Pclass	                 0	                 891	                0%
Name	                   0	                 891	                0%
Sex	                     0	                 891	                0%
**Age**	               **177**	            **891**	             **19.87%**
SibSp	                   0	                 891	                0%
Parch	                   0	                 891	                0%
Ticket	                 0	                 891	                0%
Fare	                   0	                 891	                0%
## Key Finding

The **Age** column contains **177 missing values**, which represents approximately **19.87%** of the dataset.

The remaining columns contain no missing values.

## 📊 Excel Analysis

In Excel, COUNTBLANK() was used to identify missing values.

Example:

=COUNTBLANK('Titanic-Dataset'!F2:F892)

This returned:

177

The missing percentage was calculated using:

=B7/C7
## 🐍 Python Analysis

The missing values were identified using Pandas:

missing_values = df.isnull().sum()
print(missing_values)

A complete summary was created using:

missing_summary = pd.DataFrame({
    "Missing Values": df.isnull().sum(),
    "Total Values": len(df),
    "Missing Percentage": (df.isnull().sum() / len(df)) * 100
})

print(missing_summary)

To display only columns containing missing values:

missing_summary[missing_summary["Missing Values"] > 0]
## 📈 Final Findings
The dataset contains **891 records and 10 columns**.
A total of **177 missing values** were identified.
All 177 missing values are in the **Age** column.
**19.87%** of Age values are missing.
The other columns contain no missing values.
The original dataset was kept unchanged.
##  Conclusion

The missing-value analysis successfully identified the columns containing incomplete data. The **Age** column is the only column requiring further consideration before performing additional analysis. The identified missing values can be handled using an appropriate missing-data treatment method in a future data-cleaning step.

## 👩‍💻 Project By

M. Navya Sri

Data Analytics Internship – Veda Technology
