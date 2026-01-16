# Data Cleaning Project

## Objective
The goal of this project is to perform data cleaning on two datasets by:
- Identifying missing values
- Visualizing missing data
- Applying appropriate imputation techniques
- Validating the cleaned dataset
- Comparing dataset size and quality before and after cleaning

## Datasets Used
1. House Prices Dataset  
2. Medical Appointment No Shows Dataset  

Both original and cleaned versions are included in this repository.

## Tools & Libraries
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Steps Performed
1. Loaded the datasets using Pandas.
2. Identified missing values using `.isnull().sum()`.
3. Visualized missing data using bar charts.
4. Applied median imputation for numerical columns.
5. Applied mode imputation for categorical columns.
6. Removed columns with extremely high missing values (>40%).
7. Validated the dataset after cleaning.
8. Compared dataset size and data quality before and after cleaning.

## Results
- No missing values were found in either dataset.
- Dataset size remained unchanged after cleaning.
- Data quality was preserved.

## Files in This Repository
- `House Prices Dataset.csv`
- `Medical Appointment No Shows.csv`
- `House_Prices_Cleaned.csv`
- `Medical_No_Shows_Cleaned.csv`
- `Combined_Data_Cleaning.ipynb`
- `screenshots/` (outputs & comparisons)

## Conclusion
The datasets were already clean with no missing values. The applied data cleaning steps validated the dataset quality and confirmed suitability for further analysis or machine learning tasks.
