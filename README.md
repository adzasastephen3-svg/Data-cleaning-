# Customer Data Cleaning Project

This project focuses on cleaning and preparing a customer dataset for analysis using Microsoft Excel.

The dataset contains customer information such as names, email addresses, phone numbers, countries, ages, customer types, joining dates, and total spending.

The dataset contains several data-quality issues that need to be identified, investigated, and corrected where appropriate.

This project is part of my journey learning Data Analytics, with a particular focus on developing strong data-cleaning skills.


Project Objectives

The main objectives of this project are to:

- Identify missing values.
- Detect duplicate records and investigate duplicate customer IDs.
- Remove unnecessary spaces from text.
- Standardize inconsistent capitalization.
- Identify invalid or suspicious ages.
- Standardize inconsistent gender values.
- Investigate inconsistent customer types.
- Standardize different formats of phone numbers.
- Clean and standardize email addresses.
- Check date formatting.
- Convert customer spending values into a consistent numerical format.
- Create a data-quality report documenting the problems found and the actions taken.
- Prepare a clean dataset for future analysis.

 Dataset Description

The dataset contains customer records with the following columns:

| Column | Description |
|---|---|
| Customer_ID | Unique identifier assigned to a customer |
| Customer_Name | Customer's full name |
| Email | Customer's email address |
| Phone | Customer's phone number |
| Country | Country where the customer is located |
| City | Customer's city |
| Age | Customer's age |
| Gender | Customer's gender |
| Customer_Type | Customer classification, such as Regular, Premium, or VIP |
| Join_Date | Date the customer joined |
| Total_Spend | Total amount spent by the customer |


 Data Quality Issues Investigated

### 1. Missing Values

Checked important columns for blank values, including:

- Phone
- City
- Age
- Total_Spend

Missing values were investigated rather than automatically replaced with zero.

### 2. Duplicate Records

Checked for duplicate customer records.

Duplicate records require investigation before removal because repeated customer IDs do not always mean that the entire record is duplicated.

### 3. Extra Spaces

Investigated unnecessary spaces in text fields, including customer names and other text columns.

Excel functions such as `TRIM()` can help remove unwanted spaces.

### 4. Inconsistent Capitalization

Checked for inconsistent capitalization in fields such as Country, Gender, and Customer_Type.

Functions such as `PROPER()`, `UPPER()`, and `LOWER()` can help standardize text.

### 5. Invalid or Suspicious Ages

Investigated unusual age values.

An unusual value should be investigated rather than automatically changed without evidence.

### 6. Inconsistent Gender Values

Checked for different representations of the same category, such as:

- Male
- male
- M
- Female
- female
- F

The goal is to establish a consistent format while preserving the intended meaning.

### 7. Inconsistent Customer Types

Investigated inconsistent capitalization and formatting in customer classifications.

The goal is to ensure that equivalent customer types are represented consistently.

### 8. Phone Number Formatting

Checked for different phone-number formats and investigated how to standardize them.

Phone numbers should generally be stored as text to preserve leading zeros.

### 9. Email Formatting

Checked email addresses for unnecessary spaces and inconsistent capitalization.

Cleaning should not change the intended email address.

### 10. Total Spend Formatting

Investigated spending values represented in different formats, including currency symbols, text suffixes, and missing-value labels.

The objective is to create a consistent numerical spending field without accidentally changing the amounts.

---

##  Tools and Techniques

**Tool:** Microsoft Excel

Techniques and functions relevant to this project include:

- `TRIM()`
- `PROPER()`
- `UPPER()`
- `LOWER()`
- `IF()`
- `AND()`
- `OR()`
- `COUNTIF()`
- `COUNTBLANK()`
- `VALUE()`
- `SUBSTITUTE()`
- `ISNUMBER()`
- Excel's Remove Duplicates feature
- Data validation and manual investigation

---

##  Workbook Structure

The workbook contains the following sheets:

Raw_Data

Cleaned_data

Data_Quality_Report

---

##  Data Cleaning Workflow

The workflow followed in this project is:

1. Inspect the original dataset.
2. Identify data-quality issues.
3. Investigate missing and suspicious values.
4. Check for duplicate records and duplicate IDs.
5. Standardize text and category values.
6. Clean numerical values and dates.
7. Validate the cleaned data.
8. Document findings and cleaning decisions.
9. Prepare the final dataset for analysis.



This project is designed to strengthen my understanding of:

- Data-quality assessment
- Missing-value handling
- Duplicate detection
- Text cleaning
- Category standardization
- Numerical data conversion
- Date validation
- Data validation
- Responsible data-cleaning decisions
- Documentation of cleaning processes

An important lesson is that not every unusual value is automatically an error. Some values require further investigation before they can be corrected safely.

---



My goal is to develop the ability to identify data-quality problems, select appropriate cleaning techniques, validate the results, and explain why each cleaning decision was made.
