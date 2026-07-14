Here's a professional **GitHub README.md** for your **Power BI Assignment**. You can copy and paste it directly into your GitHub repository.

# 📊 Power BI Assignment – Data Import, Transformation & Data Modeling

## 📌 Project Overview

This project demonstrates the complete data preparation and transformation workflow in **Microsoft Power BI** using **Power Query Editor**. The assignment covers importing data, cleaning, transforming, modeling, and preparing datasets for analysis.

The objective is to build a clean, structured, and analysis-ready data model by applying industry-standard data transformation techniques.

---

# 🛠️ Tools Used

* Microsoft Power BI Desktop
* Power Query Editor

---

# 📂 Dataset

The project uses multiple datasets, including:

* List of Orders
* Order Details
* Sales Target

These datasets were imported into Power BI and transformed before creating relationships.

---

# 📖 Assignment Tasks

## 1. Data Import

* Imported all required Excel datasets into Power BI.
* Verified data was loaded successfully into Power Query Editor.
* Confirmed table structure before transformation.

---

## 2. Row Limiting & Data Types

* Restricted the **List of Orders** table to the first **500 rows**.
* Converted columns into appropriate data types.
* Changed **Order Date** to the **Date** data type.
* Verified numeric and text columns were correctly formatted.

---

## 3. Text Formatting

Performed text transformation operations such as:

* Trim
* Clean
* Proper Case
* Upper Case
* Lower Case
* Standardized text formatting for consistency.

---

## 4. Column Creation

Created new columns using custom formulas to support analysis.

Examples include:

* Calculated fields
* Custom columns
* Derived values based on existing data

---

## 5. Conditional Column

Created a new conditional column named **Profit Status** using the following logic:

| Profit Value | Profit Status |
| ------------ | ------------- |
| Profit < 0   | Loss          |
| Profit = 0   | Break-Even    |
| Profit > 0   | Profit        |

This column categorizes each transaction based on its profit value.

---

## 6. Merging Data (Joins)

Merged tables using common keys to enrich the dataset.

Examples:

* Joined **List of Orders** with **Order Details**
* Verified matching records after merge
* Expanded required columns from related tables

---

## 7. Handling Missing Data & Duplicate Data

Performed data cleaning by:

* Identifying missing values
* Replacing or removing null values where appropriate
* Detecting duplicate records
* Removing duplicate rows
* Validating data quality after cleaning

---

## 8. Sorting and Filtering Data

Applied sorting and filtering to organize the dataset.

Tasks performed:

* Sorted columns in ascending and descending order
* Filtered records based on business requirements
* Removed unnecessary rows where applicable

---

## 9. Grouping and Aggregating Data

Grouped data using Power Query.

Performed aggregations such as:

* Sum
* Count
* Average
* Maximum
* Minimum

This helped summarize business information for reporting.

---

## 10. Data Modeling

Created relationships between the datasets using the **Manage Relationships** feature.

Relationships created:

| Table          | Related Table | Key      |
| -------------- | ------------- | -------- |
| List of Orders | Order Details | Order ID |
| Order Details  | Sales Target  | Category |

Modeling tasks completed:

* Created one-to-many relationships
* Verified active relationships
* Ensured proper filter direction
* Built a clean star-style data model for reporting

---

# 📊 Key Learning Outcomes

Through this assignment, I gained hands-on experience in:

* Importing data into Power BI
* Using Power Query for data transformation
* Cleaning and preparing datasets
* Creating custom and conditional columns
* Merging datasets
* Handling missing and duplicate data
* Sorting and filtering records
* Grouping and aggregating data
* Building data models with relationships
* Preparing data for business intelligence reporting

---

# 🚀 Skills Demonstrated

* Data Import
* Data Cleaning
* Power Query Editor
* Data Transformation
* Conditional Columns
* Custom Columns
* Data Merging
* Missing Value Handling
* Duplicate Removal
* Sorting & Filtering
* Grouping & Aggregation
* Data Modeling
* Relationship Management
* Power BI Desktop

---

# 📌 Conclusion

This assignment demonstrates the complete workflow of preparing raw data for analysis using Microsoft Power BI. By applying data transformation, cleaning, merging, aggregation, and data modeling techniques, the dataset was converted into a reliable and structured model ready for dashboard development and business analysis.
