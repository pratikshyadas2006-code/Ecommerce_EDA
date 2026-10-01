# E-Commerce Sales & Customer Behavior Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the UCI Online Retail Dataset to understand e-commerce sales performance, product demand, customer purchasing behavior, and sales trends.

## Objectives

- Analyze overall sales performance
- Identify top-selling and frequently ordered products
- Analyze customer purchasing behavior
- Identify high-value customers
- Examine monthly and weekly sales trends
- Analyze transaction cancellations
- Identify potential outliers
- Explore relationships between quantity, price, and sales
- Generate business insights and recommendations

## Dataset

**Dataset:** UCI Online Retail Dataset

The dataset contains e-commerce transaction information including:

- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning

The dataset was cleaned by:

- Removing duplicate rows
- Handling missing product descriptions
- Separating cancelled transactions
- Removing invalid quantities
- Removing invalid prices
- Creating a new `Sales` column

## Analysis Performed

The analysis covers:

- Product analysis
- Country analysis
- Customer analysis
- Monthly sales trends
- Weekly sales trends
- Product demand
- Customer order behavior
- Average Order Value (AOV)
- Cancellation analysis
- Outlier analysis
- Correlation analysis

## Key Metrics

- Total Sales: 10,642,110.80
- Total Quantity Sold: 5,572,420
- Total Orders: 19,960
- Unique Customers: 4,338
- Average Order Value: 533.17
- Cancellation Rate: 1.73%

## Key Insights

- Several products show consistently high demand and order frequency.
- A small group of customers contributes significantly to total sales.
- Sales vary across months and weeks.
- November 2011 recorded the highest monthly sales in the cleaned dataset.
- Potential outliers were identified in quantity, unit price, and sales.
- Cancelled transactions account for a measurable portion of the transaction records.

## Business Recommendations

- Focus inventory planning on frequently ordered products.
- Monitor high-value customers and encourage repeat purchases.
- Investigate reasons behind cancelled transactions.
- Use sales trends for inventory and promotional planning.
- Investigate unusual quantities and prices to distinguish genuine transactions from possible data issues.

## Project Files

- `ECommerce_EDA.ipynb` — Complete exploratory data analysis
- `dataset/Online Retail.xlsx` — Dataset used for the analysis

## Conclusion

The analysis provides a detailed view of e-commerce sales, products, customers, and purchasing trends. The findings can support better inventory planning, customer retention, and sales decision-making.