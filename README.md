# Data Preprocessing Tools

A practical walkthrough of the essential data preprocessing steps needed before training any machine learning model. Built as part of a Data Science and Machine Learning course at Birzeit University.

## About

This notebook covers the standard preprocessing pipeline applied to a small dataset of 10 records with country, age, salary, and a binary purchase outcome. Each step prepares the raw data for use in a machine learning algorithm.

## Steps Covered

1. Importing and exploring the dataset, splitting features (X) from the target variable (y).
2. Handling missing values in age and salary columns using mean imputation via SimpleImputer.
3. Encoding categorical data: OneHotEncoder for the country column (France, Spain, Germany) and LabelEncoder for the Yes/No target.
4. Splitting into training (80%) and test (20%) sets with train_test_split.
5. Feature scaling using StandardScaler on the numeric columns to normalize value ranges.

## Tools

- Python
- NumPy, Pandas, Matplotlib
- scikit-learn (SimpleImputer, OneHotEncoder, LabelEncoder, StandardScaler)

## Author

Ehab Ellati
