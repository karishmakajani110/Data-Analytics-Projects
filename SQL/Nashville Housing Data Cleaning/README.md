# Nashville Housing Data Cleaning using SQL

## Project Overview
This project focuses on cleaning and transforming a real-world housing dataset using SQL to
improve data quality and prepare it for analysis and reporting.

The dataset contains approximately 56,000 housing records from Nashville.

## Tools & Technologies
- SQL
- Microsoft SQL Server (SSMS)

## Data Source
- Sample Nashville housing dataset used for SQL data cleaning practice

## Data Cleaning & Transformation
The following data cleaning steps were performed using SQL functions and techniques:

- Standardized date formats using CONVERT
- Populated missing property address data using SUBSTRING, CHARINDEX, and ISNULL
- Split address fields into individual columns (Address, City, State) using PARSENAME and REPLACE
- Converted "Y" and "N" values to "Yes" and "No" in the *Sold as Vacant* field using CASE statements
- Removed duplicate records using ROW_NUMBER() with PARTITION BY
- Dropped unused and irrelevant columns to streamline the dataset

## Outcome
The final output is a clean, structured dataset suitable for downstream analysis, reporting,
or visualization.

## Key Takeaway
This project demonstrates strong SQL-based data cleaning skills and highlights the importance
of preparing raw data before meaningful analysis can be performed.


