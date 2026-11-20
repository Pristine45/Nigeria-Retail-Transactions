# Nigeria-Retail-Transactions - Data Cleaning and Quality Assessment

## Project Overview 

This project focuses on cleaning, standardizing and assessing the data quality of a Nigerian retail transactions using Microsoft Excel
The dataset contained inconsistencies, missing values, duplicate records, incorrect formats, spelling errors and invalid dates. The objective was to improve data accuracy, consistency, completeness, and reliability to make the dataset suitable for further analysis.

## Project Objectives

- Identify and remove duplicate records.
- Detect and correct missing and inconsistent values.
- Standardize text entries, dates and numerical identifiers.
- Validate relationships between related columns.
- Assess the quality of the dataset before and after cleaning.
- Prepare a structured dataset suitable for data analysis.

## Dataset Description

| Description | Details |
|---|---|
| Dataset Name | Nigerian Retail Transactions |
| Original Records | 20,350 |
| Final Records | 20,000 |
| Original Columns | 15 |
| Duplicates Removed | 350 |
| Tool Used | Microsoft Excel |

### Dataset Columns

1. Transaction ID
2. Transaction Date
3. Cleaned Transaction Date
4. Store Name
5. Store ID
6. City
7. State
8. Product ID
9. Product Name
10. Product Category
11. Quantity
12. Unit Price
13. Total Amount
14. Payment Method
15. Cashier ID

## Data Quality Issues Identified

The original dataset contained several data quality problems:

- Duplicate transaction records.
- Missing and invalid dates.
- Inconsistent date formats.
- Incorrect spelling of store and product names.
- Inconsistent capitalization and text formatting.
- Missing and incorrectly formatted identifiers.
- Inconsistent city and state entries.
- Missing or incorrect product information.
- Missing and inconsistent numerical values.
- Inconsistent payment method entries.

## Data Cleaning Process

The following cleaning procedures were performed:

### 1. Duplicate Removal
Identified and removed 350 duplicate records, reducing the dataset from 20,350 to 20,000 records.

### 2. Text Standardization
Corrected spelling errors, unnecessary spaces, inconsistent capitalization and improper text formatting.

### 3. Date Cleaning
Standardized valid dates into a consistent date-only format. Missing and invalid dates were identified and labelled as "Invalid Dates" rather than assigning unverified values.

### 4. Identifier Standardization
Standardized Transaction IDs, Store IDs, Product IDs and Cashier IDs by removing unnecessary prefixes and formatting inconsistencies.

### 5. Missing and Incorrect Value Correction
Reviewed missing and incorrect entries using related columns to identify values that could be reliably corrected.

### 6. Cross-Column Validation
Validated related fields to improve data consistency:

- Store Name against Store ID.
- City against State.
- Product ID against Product Name.
- Product Name against Product Category.
- Quantity, Unit Price and Total Amount against one another.

## Tools and Excel Functions Used

**Tool:** Microsoft Excel

**Functions and Features:**
- TRIM
- PROPER
- IF
- COUNTIF
- COUNTIFS
- Conditional Formatting
- Find and Replace
- Remove Duplicates
- Data Validation

## Project Files

| Folder | Contents |
|---|---|
| Data | Original and cleaned datasets |
| Documentation | Data cleaning report and data quality assessment |
| Screenshots | Visual evidence of the cleaning process |

## Key Results

- Removed 350 duplicate records.
- Reduced the dataset from 20,350 to 20,000 records.
- Standardized inconsistent text and identifier formats.
- Corrected missing and incorrect entries where reliable validation was possible.
- Identified 136 missing or invalid transaction dates.
- Improved consistency across related dataset columns.
- Prepared the cleaned dataset for subsequent analysis.

## Limitations

Some transaction dates could not be independently verified. These were retained as invalid rather than replaced with assumed values.

## Conclusion

This project demonstrates practical data cleaning, data validation and data quality assessment skills using Microsoft Excel.
It highlights the importance of identifying inconsistencies, applying appropriate cleaning techniques, validating related fields and documenting data quality issues before conducting further analysis.

**Project Category:** Data Analytics | Data Cleaning | Data Quality Assessment

**Tool:** Microsoft Excel

It highlights the importance of identifying inconsistencies, applying appropriate cleaning techniques, validating related fields, and documenting data quality issues before conducting further analysis.
