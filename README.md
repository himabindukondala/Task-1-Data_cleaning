# Task-1-Data_cleaning & Preparation

# Objective
To clean and prepare a raw e-commerce dataset by handling missing values, checking duplicates, and correcting data formats using Python and Google Colab.

# Tools Used
- Python
- Pandas
- NumPy
- Google Colab

# Dataset Information
- Total Records: 1200
- Total Columns: 14

# Data Cleaning Steps
1. Loaded the dataset into Google Colab.
2. Checked dataset structure using `df.info()`.
3. Identified missing values using `df.isnull().sum()`.
4. Found 309 missing values in the `CouponCode` column.
5. Replaced missing CouponCode values with `"No Coupon"`.
6. Checked for duplicate records using `df.duplicated().sum()`.
7. Verified and formatted the Date column.
8. Performed final verification to ensure no missing values or duplicate records remained.

# Results

- Missing values handled successfully.
- No duplicate records found.
- Date format standardized.
- Dataset cleaned and prepared for analysis.

# Output

The cleaned dataset was exported as:
```python
df.to_csv("cleaned_dataset.csv", index=False)
```
# Conclusion

The dataset was successfully cleaned and prepared for further analysis by handling missing values, verifying duplicates, and ensuring data consistency.
