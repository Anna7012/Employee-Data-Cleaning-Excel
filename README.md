# Employee Data Cleaning Using Microsoft Excel

## 📌 Project Overview
This project focuses on cleaning and organizing a messy employee dataset using Microsoft Excel. The objective is to improve data quality by identifying and correcting inconsistencies, handling missing values, and preparing the dataset for further analysis.

## 🎯 Project Objectives
- Identify and handle missing values.
- Remove unwanted spaces and standardize text.
- Separate department and region information.
- Standardize date and email formats.
- Identify duplicate employee IDs.
- Check invalid or inconsistent values.
- Prepare a clean and structured dataset.

## 📂 Dataset Information

The dataset contains 25 employee records with 12 original columns.

**Original columns:**
- Employee_ID
- First_Name
- Last_Name
- Age
- Department_Region
- Status
- Join_Date
- Salary
- Email
- Phone
- Performance_Score
- Remote_Work

The `Department_Region` column was separated into two columns: `Department` and `Region`.

## 🛠️ Tools Used
- Microsoft Excel
- Excel Formulas
- Conditional Formatting
- Text to Columns
- Data Validation
- Excel Tables

## 🧹 Data Cleaning Steps

1. Created a separate worksheet for cleaned data while preserving the original dataset.
2. Removed unnecessary spaces from text fields using `TRIM()`.
3. Standardized names and text using `PROPER()`.
4. Converted email addresses to lowercase using `LOWER()`.
5. Separated Department and Region using Text to Columns.
6. Formatted date and salary columns.
7. Identified missing values in the Age column.
8. Checked employee IDs for duplicates.
9. Reviewed phone numbers and other data inconsistencies.
10. Applied formatting and converted the cleaned dataset into an Excel Table.

## 📊 Project Structure

```text
Employee-Data-Cleaning-Excel/
│
├── Employee_Data_Cleaning.xlsx
└── README.md
```

## 📁 Excel Workbook Sheets

The Excel workbook contains:

- **Messy_Employee_dataset:** Original dataset.
- **Cleaned_Data:** Cleaned and organized employee data.
- **Data Quality Report:** Summary of data quality checks.

## 📈 Outcome

The project demonstrates practical data-cleaning skills using Microsoft Excel. The final workbook provides a more organized dataset and a data quality report that can support further data analysis.

## 👩‍💻 Author
ANNA J JOSEPH
Engineering Student | AI & Data Science  
Interested in Data Analytics and Business Analytics.
