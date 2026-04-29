<img width="912" height="828" alt="image" src="https://github.com/user-attachments/assets/4ae5dd9f-a85b-4515-92b1-91ae8b2eb7a9" /># dataImmersionWrangling-retail-sales
Data cleaning and wrangling of a retail sales dataset using Python (Pandas)
# Data Immersion & Wrangling - Retail Sales

## Overview
This project focuses on data immersion, data quality assessment, cleaning, and transformation of a retail sales dataset using Python and Pandas. The goal is to convert the raw transactional dataset into an analysis-ready dataset for further business insights.

## Objective
The objective of this task is to:
- Understand the structure and meaning of the dataset.
- Assess data quality issues such as missing values, duplicates, inconsistencies, and outliers.
- Clean and transform the dataset.
- Create useful new features for analysis.
- Produce a final cleaned dataset and supporting project files.

## Dataset Information
The dataset used in this project contains retail transaction records with the following columns:
- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

Each row represents one retail transaction.

## Tools and Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook
- GitHub

## Project Workflow

### 1. Data Access and Familiarization
- Loaded the dataset into Pandas.
- Inspected shape, columns, data types, and sample rows.
- Built a data dictionary to understand each field.

### 2. Data Quality Assessment
- Checked for missing values.
- Checked for duplicate rows and duplicate transaction IDs.
- Verified whether Total Amount equals Quantity × Price per Unit.
- Reviewed numerical columns for possible outliers.

### 3. Data Cleaning and Transformation
- Converted the Date column into datetime format.
- Standardized column names into snake_case.
- Cleaned categorical values for consistency.
- Removed duplicate records if present.
- Filled missing values where necessary.
- Recalculated total_amount for consistency.

### 4. Feature Engineering
Created the following new columns:
- year
- month
- month_name
- day_name
- age_group
- spending_level

### 5. Final Output
The final deliverables generated in this project are:
- Cleaned dataset
- Data dictionary
- Jupyter/Colab notebook
- GitHub repository documentation

## Repository Files
- `retail_sales_dataset.csv` → Raw dataset
- `retail_sales_cleaned.csv` → Cleaned dataset
- `data_dictionary.csv` → Data dictionary
- `data_wrangling_retail_sales.ipynb` → Full notebook/code
- `README.md` → Project documentation
- `.gitignore` → Ignored unnecessary files
- `LICENSE` → Project license

## How to Run the Project
1. Download or clone this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Upload the dataset file if required.
4. Run all cells step by step.
5. The final cleaned dataset will be generated as `retail_sales_cleaned.csv`.

## Key Learning Outcomes
- Hands-on experience with data wrangling.
- Understanding of data quality assessment.
- Practical use of Pandas for cleaning and transformation.
- Preparing real-world business data for analysis.

## Author
**Manikanta Chappa**

## License
This project is licensed under the MIT License.
