# Project Summary

## Data Quality Issues Identified

- Missing values were found in the `Age`, `Cabin`, and `Embarked` columns.
- A high number of missing values were found in the `Cabin` column (687 out of 891 records missing).
- No duplicate records were found.
- `Fare` column allows 4 decimal places which reduces readability, and `Sex` column requires standardization.

## Cleaning Techniques Applied

- Removed the `Cabin` column due to the high number of missing values.
- Filled the missing values in the `Age` column with the median.
- Filled the missing values in the `Embarked` column with the mode.
- Rounded the `Fare` column to 2 decimal places and renamed selected column names to enhance readability.

## Assumptions Made

- The median was considered the most appropriate measure to fill missing values in the `Age` column to avoid distortion due to outliers.
- The mode was used to fill missing values in the `Embarked` column since it represents the most frequently occurring value.

## Key Observations

- After preprocessing, the dataset contained no missing values and remained free of duplicate records.
- The cleaned dataset is consistent and ready to be used for further analysis.

