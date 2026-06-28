# -OIBSIP-
Data analysis and Exploratory Data Analysis (EDA) projects developed as part of the Oasis Infobyte Internship (OIBSIP).
# Retail Sales Data Analysis

## Project Overview
Performed Exploratory Data Analysis (EDA) on a retail sales dataset using Python.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Insights
- Monthly sales trends
- Customer demographics analysis
- Product category performance
- Correlation analysis

## Business Recommendations
- Target high-spending age groups
- Optimize inventory for top-selling products
- Plan promotions during peak seasons

*Shape: Number of rows and columns (e.g., (1000, 15)).

*Columns: List of all column names.

*Data Types: Data type (int64, float64, object, etc.) of each column.

*Head: Preview of the first five records.

*Info: Summary including non-null counts and memory usage.

*Null Values: Number of missing values in each column.

*Total Null Values: Total missing values across the entire dataset.


| Column     |   Mean | Median |   Mode | Standard Deviation |
| ---------- | -----: | -----: | -----: | -----------------: |
| Age        |   34.8 |     35 |     30 |               8.21 |
| Salary     | 52,300 | 50,000 | 45,000 |             11,450 |
| Experience |    9.2 |      9 |      8 |               3.54 |


*Converts the Date column to a datetime format. 

*Sets the Date column as the index.

*Aggregates sales by month using resample('M').sum().

*Aggregates sales by quarter using resample('Q').sum().

*Plots separate line charts for monthly and quarterly sales trends with markers and gridlines.
