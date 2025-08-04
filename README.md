# ☕ Café Sales Analysis (Power BI)

This project presents a sales analysis for a fictional café using Power BI. The dataset includes 10,000+ sales transactions, and the goal is to extract actionable insights to help improve product performance, customer experience, and operational decisions.

## 📊 Project Objectives

- Clean and prepare raw sales data for analysis.
- Build a star schema data model using Power BI.
- Create DAX measures to calculate KPIs such as:
  - Total Revenue
  - Total Quantity Sold
  - Number of Transactions
- Design an interactive Power BI report with filters and slicers.


## 🧹 Data Preparation

The dataset contained missing and inconsistent values. Cleaning steps included:
- Replacing `ERROR`, `UNKNOWN`, and blanks with `null` or `"Unknown"` where appropriate.
- Calculating missing `Price per Unit`, `Quantity`, or `Total Spent` using available values.
- Removing rows with missing critical data (e.g., item, date).
- Creating a `Category` column for grouping items (e.g., Beverage, Food, Dessert).
- Building a star schema: `Fact_Sales`, `Dim_Item`, `Dim_Date`.


## 📁 Report Pages Overview

1. **Sales Overview** – KPIs and revenue trends
2. **Sales by Item & Category** – Top-performing items and category breakdowns
3. **Location & Payment Analysis** – Performance segmented by sales channel and payment method
4. **Price & Quantity Trends** – Unit price and volume analysis
5. **Insights & Recommendations** – Key takeaways + data quality warning



## ⚠️ Data Quality Note

Over 30% of the records had missing values for `Location` and `Payment Method`, marked as `"Unknown"`. This limits the reliability of certain breakdowns. Recommendation: improve data capture at the point of sale.




## 📌 Status

✅ In progress



## Author

**Rania OUTAYEB**
💼 Junior Data Analyst  
📧 [Your email or LinkedIn if you want to include it]

