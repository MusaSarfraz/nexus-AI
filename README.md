
# Task1_EDA_NEXUSAI
# Task 1: Exploratory Data Analysis (EDA)

## Overview
Perform exploratory data analysis on the Online Retail dataset. Clean the data, compute statistics, create visualizations, and extract business insights.

## Steps
1. Load `OnlineRetail.csv`
2. Clean data:
   - Remove duplicates
   - Convert `InvoiceDate` to datetime
   - Drop rows with missing `CustomerID`
   - Add `Sales = Quantity × UnitPrice`
3. Compute descriptive statistics for Quantity, UnitPrice, and Sales
4. Visualizations:
   - Histogram of Sales
   - Bar chart of Top 10 Products by Sales
   - Line chart of Sales Over Time
5. Save cleaned dataset as `cleaned_data.csv`
6. Print 5 key business insights:
   - Country with highest sales
   - Peak sales month
   - Best-selling product
   - Average order value
   - Unique customers and transactions

## Output
- Cleaned dataset: `cleaned_data.csv`
- Statistical summaries
- Visualizations
- Printed insights
