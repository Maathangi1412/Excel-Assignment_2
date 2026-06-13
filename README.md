Excel Data Cleaning Assignment – Product Dataset

Project Overview

This project demonstrates data cleaning and transformation using Microsoft Excel and Power Query Editor. The objective is to convert a raw dataset containing inconsistencies, missing values, duplicates, and unstructured data into a clean and analysis-ready dataset.

The dataset used is a Product Dataset containing Product ID, Product Name, Brand Name, Quantity, Category, and Price.

Objectives
Handle missing values
Correct inconsistent data entries
Remove duplicate records
Split and merge columns
Apply proper number formatting
Use conditional formatting for visualization

Dataset Description
Dataset Name: Product Dataset

Columns:
Product ID
Product Name
Brand Name
Quantity
Category
Price

Data Cleaning Steps

1. Handling Missing Values
Missing values in the Price column were replaced using the average price of each category to maintain consistency.

2. Correcting Inconsistent Data
In Power Query Editor, Replace Values was used to fix inconsistencies in Category and Brand Name columns. For example, “Electroni” was replaced with “Electronics”.

3. Removing Duplicates
Duplicate rows were removed using Power Query Editor’s Remove Duplicates feature to ensure uniqueness of records.

4. Splitting and Merging Columns
The Product ID column was split into Manufacturing Date and Country Code.
Unnecessary characters were removed during transformation.
Brand Name and Product Name columns were merged into a new column called Product Brand using a custom column formula.

5. Number Formatting
Price column formatted as Currency
Manufacturing Date formatted as DD-MM-YYYY

6. Conditional Formatting
Data Bars applied to Price column for visual comparison
Custom rule applied to highlight Category = Electronics

Deliverables
Cleaned and transformed dataset in Excel
PDF containing screenshots of all cleaning steps
README documentation

Project Structure
Excel Assignment_2/
1. Cleaned and Transformed Dataset.xlsx
2. PDF of Screenshots.pdf
3. README.md

Tools Used
Microsoft Excel
Power Query Editor
Conditional Formatting
Data Transformation Tools

Outcome
This project demonstrates practical data preprocessing skills including cleaning, transformation, and visualization using Excel, preparing raw data for meaningful analysis.
