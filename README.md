# E-Commerce Sales Data Cleaning Using Python
## Internship Project 1
This project focuses on cleaning and preprocessing an e-commerce sales dataset using Python and pandas to improve data quality, ensure consistency, and prepare the dataset for exploratory data analysis.

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
The dataset contains e-commerce transaction records including:
- Customer information
- Product purchases
- Payment methods
- Order statuses
- Coupon usage
- Revenue-related fields

---

## Project Workflow

The workflow for this project followed the standard data cleaning pipeline:

1. Dataset Inspection  
2. Missing Value Handling  
3. Duplicate Validation  
4. Datatype Verification  
5. Text Standardization  
6. Numerical Validation  
7. Exporting Cleaned Dataset  

The cleaned dataset was then prepared for exploratory data analysis in the next phase of the internship project.

--- 
## Tools and Technologies Used
- Python
- pandas
- Numpy
- Jupyter Notebook
- Microsoft Excel
---

## Data Cleaning Process

### 1. Missing Value Handling
Missing values were checked across all columns in the dataset.  
Missing values identified in the `CouponCode` column were replaced with `"NO COUPON"` to indicate transactions without promotional discounts.

### 2. Duplicate Validation
The dataset was examined for duplicate records to ensure data consistency and reliability.

### 3. Datatype Validation
Dataset datatypes were reviewed to confirm that numerical, categorical, and date-related columns were already formatted appropriately for analysis.

### 4. Text Standardization
Categorical columns were cleaned by:
- Removing unnecessary spaces
- Standardizing capitalization
- Ensuring consistent text formatting

### 5. Categorical Value Validation
Unique values within categorical columns were reviewed to identify formatting inconsistencies and spelling variations.

### 6. Numerical Validation
A validation check was performed on the `TotalPrice` column to confirm that:

`TotalPrice = Quantity × UnitPrice`

The validation confirmed that the revenue calculations were consistent across the dataset.

### 7. Exporting Cleaned Dataset
The cleaned dataset was exported successfully for further analysis and reporting.

---

## Skills Demonstrated

This project demonstrates practical skills in:

- Data Cleaning
- Data Validation
- Data Preprocessing
- Data Quality Assessment
- Python Programming
- pandas Data Manipulation
- Dataset Documentation

---

## Files Included

| File | Description |
|---|---|
| `dataset for analytics.xlsx` | Original raw dataset |
| `cleaned_dataset.xlsx` | Cleaned dataset after preprocessing |
| `project1_data_cleaning.ipynb` | Jupyter Notebook containing the data cleaning workflow |
| `project1_data_cleaning.html` | HTML export of the notebook |
| `README.md` | Project documentation |

---

## Future Work

The cleaned dataset from this project will be used for:

- Exploratory Data Analysis (EDA)
- Sales trend analysis
- Customer behavior analysis
- Revenue analysis
- SQL-based business querying

---

## Conclusion

This project successfully cleaned and prepared an e-commerce sales dataset for downstream analysis.

The cleaning process improved dataset consistency, validated numerical accuracy, standardized categorical values, and ensured overall data reliability for future analytical tasks.

