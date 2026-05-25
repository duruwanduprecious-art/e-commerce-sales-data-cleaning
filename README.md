# E-Commerce Sales Data Cleaning Using Python
## Internship Project 1
This project focuses on cleaning and preprocessing an e-commerce sales dateset using Python and pandas to improve data quality, ensure consistency, and prepare the dataset for exploratory data analysis.
---
## Project Objectives
The main objectives of this project were to:
- Identify and handle missing values
- Remove duplicates
- Validate data consistency and accuracy
- Standardize categorical fields
- Prepare a clean dataset suitable for analysis and reporting
---
## Dataset Description
The dataset contains e-commerce transaction records including
- Customer information
- Product purchases
- Payment methods
- Order statuses
- Coupon usage
- Revenue-related fields
---
## Tools and Technologies Used
- Python
- pandas
- Numpy
- Jupyter Notebook
- Microsoft Excel
---
## Data Cleaning Process
The following cleaning steps were performed:
### 1. Missing Value Handling
- Checked for null values across all columns
- Replaced missing CouponCode values with '"NO COUPON"'
### 2. Duplicate Check
- Verified the dataset for duplicate records
### 3. Datatype validation
- Reviewed dataset datatypes to confirm consistency and suitability for analysis
- Verified that numerical and date-related columns already contained appropriate datetypes
### 4. Categorical Value Validation
- Reviewed unique values within text columns
- Checked for formatting inconsistency and spelling variations
### 5. Text Standardization
- Removed unnecessary spaces from categorical columns
- Standardized text capitalization for consistency
### 6. Numercal Validation
- Validated TotalPrice calculations using:
  TotalPrice = Quantity x UnitPrice
### 7. Exporting Cleaned Dataset
- Exported the cleaned dataset for further analysis
---
## Key Cleaning Outcomes
- Missing values were suceefully handled
- No duplicate records were identified
- Text inconsistencies were standardized
- Numerical calculations were validated
- The dataset was prepared sucessufully for exploratory data analysis
---

- 


