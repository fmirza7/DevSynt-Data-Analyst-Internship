# Titanic Dataset: Data Preparation & Cleaning

## Overview

This repository contains **Project 1** completed as part of the **Data Analyst Internship Program at DevSynt**.

The objective of this project was to inspect, clean, and prepare the Titanic dataset for analysis using **Python** and **Pandas**.

---

## Dataset

* **Dataset:** Titanic Dataset
* **Source:** https://www.kaggle.com/datasets/yasserh/titanic-dataset

---

## Tools Used

* Python
* Pandas
* Jupyter Notebook

---

## Data Preparation Tasks

The following preprocessing steps were performed:

* Inspected the dataset and identified data quality issues.
* Checked for missing values and duplicate records.
* Removed the `Cabin` column due to a high number of missing values.
* Filled missing values in the `Age` column using the median.
* Filled missing values in the `Embarked` column using the mode.
* Standardized the values in the `Sex` column.
* Rounded the `Fare` column to two decimal places.
* Renamed selected columns for improved readability.
* Exported the cleaned dataset as `cleaned_titanic.csv`.
