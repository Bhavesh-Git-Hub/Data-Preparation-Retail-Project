# Project Overview


The workflow follows industry-standard data preprocessing practices used in real-world data science projects.

## Objectives

- Load and explore raw transactional data
- Handle missing values and inconsistencies
- Remove duplicate records
- Perform data transformation and normalization
- Encode categorical variables
- Create meaningful engineered features
- Export a clean, analysis-ready dataset

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Data Loading

- Loaded dataset from Excel file using Pandas
- Verified structure and initial dataset integrity

### 2. Data Understanding

- Used `head()`, `info()`, and `describe()` for exploration
- Identified missing values
- Analyzed dataset structure and data types

### 3. Data Cleaning

- Removed records with missing `CustomerID`
- Filled missing values where appropriate
- Removed duplicate transactions
- Converted `InvoiceDate` to datetime format
- Corrected numerical data types

### 4. Data Transformation

- Applied `StandardScaler` for numerical normalization
- Performed One-Hot Encoding on categorical variables
- Structured dataset for machine learning compatibility

### 5. Feature Engineering

Created meaningful features to enhance analysis:

- `TotalAmount = Quantity x UnitPrice`
- Invoice Year
- Invoice Month
- Invoice Day
- Invoice Weekday
- Return Indicator feature

These features improve predictive capability and business insights.

## Project Files

- `Data_Preparation_Submission_FIXED.ipynb` -> Complete preprocessing notebook
- `cleaned_normalized_data_fixed.csv` -> Final processed dataset
- `Online Retail.xlsx` -> Original dataset

## Final Output

The final dataset:

- Is cleaned and duplicate-free
- Has corrected data types
- Contains normalized numerical features
- Includes encoded categorical variables
- Contains engineered business-relevant features
- Is ready for machine learning or analytics tasks

