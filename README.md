# Customer Personality Analysis

## Project Overview
This project was completed as part of the Elevate Labs Data Analyst Internship. The objective was to clean and preprocess the *Customer Personality Analysis* dataset using Python and perform exploratory data analysis (EDA). The final output is a clean, structured dataset ready for further modeling or insights.

---

## Tasks Completed

### Data Cleaning
- Removed duplicate rows
- Standardized column names (lowercase, underscores)
- Converted `Dt_Customer` to datetime format
- Handled missing values (`Income` filled with median)
- Corrected data types for `year_birth` and `income`

### Feature Engineering
- Created `age` from `year_birth`
- Created `customer_tenure` from `Dt_Customer`
- Created `total_spend` by summing all product-related columns

### Encoding
- One-hot encoded `education` and `marital_status` columns (drop_first=True)

### Visualizations
- Histogram of Age distribution
- Bar plots of education and marital status
- Scatter plots for:
  - Age vs Total Spend
  - Income vs Total Spend
- Correlation heatmap of all numeric features

---

## Files Included

| File Name                          | Description                                   |
|-----------------------------------|-----------------------------------------------|
| `customer_personality_analysis.ipynb` | Full notebook with code, EDA, and visuals     |
| `cleaned_customer_personality.csv`   | Final cleaned dataset (submission ready)      |
| `README.md`                          | This file                                     |
| `images/` (optional)                 | Folder for visual charts (if added separately)|

---

## Tools Used
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Dataset Source
- Kaggle: [Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

---

## What I Learned
- Real-world data cleaning using Pandas
- Handling missing values and data types
- Creating meaningful features for analysis
- Using visualizations to reveal insights
- Delivering clean, professional projects using GitHub

---

## Project Type
**EDA | Data Cleaning | Preprocessing | Internship Task**

