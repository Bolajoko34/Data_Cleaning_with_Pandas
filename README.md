# Project Title
Data Cleaning with Pandas

# Overview
This project focuses on cleaning and preparing a raw dataset for analysis. The original dataset contains multiple sheets, but this project uses only three sheets: money supply, interest rate, and mobile money.

The data had missing values, inconsistent column names, and unnecessary columns. The goal was to clean and structure the data into an analysis-ready format.

# Problem Statement
The raw dataset was not ready for analysis due to:

* Missing values across key variables
* Inconsistent and unclear column names
* Presence of irrelevant and empty columns
* Multi-sheet structure with unused data

# Objectives

* Clean and standardize column names
* Handle missing values
* Remove duplicates and irrelevant columns
* Work with selected sheets only: money supply, interest rate, and mobile money
* Prepare dataset for analysis and visualization

# Tools Used

* Python
* Pandas
* Jupyter Notebook

# Data Source

 * Bank of Ghana
 * Ghana Statistical Service
 * World Bank

# Dataset Description
The dataset consists of multiple sheets. For this project, only the following were used:

* Mobile Money (Global Findex):
Usage and ownership across regions
* Money Supply (Monetary Survey):
Deposit levels and liquidity trends
* Interest Rate (Regional and Demographic Data):
Linked financial indicators to regions and population (39 million estimated from age groups)

Each sheet required cleaning before analysis due to structural inconsistencies and missing data.

# Key Steps

1. Data Inspection
 * Used info(), describe(), and head() to understand structure and issues
2. Data Cleaning
 * Standardized column names to consistent format
 * Replaced empty values with NaN
 * Handled missing values using forward fill based on dataset structure
 * Removed empty and unnecessary columns
 * Selected only relevant sheets for analysis
3. Data Validation
 * Checked for duplicates
 * Verified dataset shape before and after cleaning
 * Confirmed missing values were handled

# Before Cleaning

* Missing values present
* Inconsistent column names
* Unstructured multi-sheet data
* Redundant and empty columns

# After Cleaning

* Standardized column names
* Missing values handled appropriately
* Only relevant sheets retained
* Clean and structured dataset ready for analysis

# Results

* Clean datasets for money supply, interest rate, and mobile money
* Data ready for visualization or analysis

# Project Structure

data-cleaning-with-pandas/

├── data/
│ ├── raw_data.xlsx
│ ├── money_supply_cleaned.xlsx
│ ├── interest_rate_cleaned.xlsx
│ └── mobile_money_cleaned.xlsx

├── notebook/
│ └── data_cleaning.ipynb/script

├── README.md

