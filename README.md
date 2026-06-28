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

#dataser.csv

*Shape: Number of rows and columns (e.g., (1000, 15)).

*Columns: List of all column names.

*Data Types: Data type (int64, float64, object, etc.) of each column.

*Head: Preview of the first five records.

*Info: Summary including non-null counts and memory usage.

*Null Values: Number of missing values in each column.

*Total Null Values: Total missing values across the entire dataset.

#mean,meadian,mode

| Column     |   Mean | Median |   Mode | Standard Deviation |
| ---------- | -----: | -----: | -----: | -----------------: |
| Age        |   34.8 |     35 |     30 |               8.21 |
| Salary     | 52,300 | 50,000 | 45,000 |             11,450 |
| Experience |    9.2 |      9 |      8 |               3.54 |

#monthly and quartely sales

*Converts the Date column to a datetime format. 

*Sets the Date column as the index.

*Aggregates sales by month using resample('M').sum().

*Aggregates sales by quarter using resample('Q').sum().

*Plots separate line charts for monthly and quarterly sales trends with markers and gridlines.

##age and gender prediction using chart




#Age Group Distribution

Age Group Distribution: A bar chart showing the number of customers in each age group (e.g., <18, 18–25, 26–35, etc.).

Gender Breakdown: A pie chart displaying the percentage of customers by gender.
Printed tables showing the counts for each age group and gender.

##gender breakdown piechart

<img width="562" height="447" alt="image" src="https://github.com/user-attachments/assets/57be1ccc-9865-44af-91bd-3f618aa5bd93" />

##customer age group discussion

<img width="1045" height="417" alt="image" src="https://github.com/user-attachments/assets/b14e0bc9-cf79-4a3b-a660-cc835cca18a4" />

For Product Analysis, the standard visualizations are:

Top 10 Best-Selling Products – Horizontal bar chart
Revenue by Product Category – Vertical bar chart

1. Top 10 Best-Selling Products

   <img width="1107" height="430" alt="image" src="https://github.com/user-attachments/assets/01fb5ecd-d8de-43d0-8b97-2a4ba681cba4" />

   2. Revenue by Product Category

   <img width="1117" height="465" alt="image" src="https://github.com/user-attachments/assets/2527ab82-dcfd-4999-a3dd-608a64651440" />


What the heatmap shows
+1.00 (Dark Red): Strong positive correlation

0.00 (White): No linear correlation

−1.00 (Dark Blue): Strong negative correlation

| Correlation (r) | Interpretation                 |
| --------------: | ------------------------------ |
|    0.80 to 1.00 | Strong positive relationship   |
|    0.50 to 0.79 | Moderate positive relationship |
|    0.20 to 0.49 | Weak positive relationship     |
|   -0.19 to 0.19 | Little or no relationship      |
|  -0.20 to -0.49 | Weak negative relationship     |
|  -0.50 to -0.79 | Moderate negative relationship |
|  -0.80 to -1.00 | Strong negative relationship   |



A good additional visualization that reveals a non-obvious insight is a scatter plot of Discount vs Profit. This helps identify whether offering higher discounts actually leads to lower profits, which may not be obvious from summary statistics alone.

Additional Visualization: Discount vs Profit (Scatter Plot)
Discount vs Profit

Relationship between discount percentage and profit. The chart can reveal whether high discounts reduce profitability.




<img width="1075" height="452" alt="image" src="https://github.com/user-attachments/assets/01122026-1a29-4195-89d7-5c23b92f3fda" />
