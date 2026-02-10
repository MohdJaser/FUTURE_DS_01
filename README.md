# Business Sales Performance Analytics – Task 1 (2026)  
**Future Interns Internship Program**

## Project Overview
This project analyzes sales performance using the **Superstore Sales Dataset** to uncover key business insights on revenue drivers, sales trends over time, category performance, regional profitability, and product-level contributions.

The analysis answers core business questions:
- Which products generate the most revenue?
- How do sales and profit vary over time (trends, seasonality)?
- Which categories and regions perform best or worst?
- Where should the business focus efforts to maximize growth and profitability?

This simulates real-world sales analytics work for retail, e-commerce, or distribution companies.

## Dataset
- **Source**: [Superstore Sales Dataset – Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **File**: `Sample - Superstore.csv`
- **Rows**: ~9,994 order lines
- **Key columns**: Order Date, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit, Region

## Tools Used
- Microsoft Excel (data cleaning, pivot tables, charts)

## Key Steps Performed
1. **Data Cleaning**
   - No duplicates found after checking with Row ID and Order ID + Product ID
   - No significant missing values in critical columns (Sales, Profit, Quantity, Region, Category)
   - Fixed data types (Order Date as Date, numeric columns for Sales/Profit)
   - Added calculated columns (Year/Month from Order Date, Profit Margin)

2. **Analysis**
   - Calculated KPIs: Total Sales, Total Profit, Average Order Value, Total Orders
   - Top products by revenue
   - Sales trends over time (monthly/yearly)
   - Sales and Profit by Category and Region

3. **Main Findings**
   - Total Sales: ~$2.3M
   - Total Profit: ~$286K
   - Technology category drives the highest sales and profit
   - West region leads in sales volume, but Central region has lower profit margins
   - Strong seasonal peaks in Q4 (November–December holiday season)

4. **Dashboard**
     - KPIs (Total Sales, Profit, Avg Order Value, Total Orders)
     - Bar chart: Top products by revenue
     - Line/column charts: Sales trends over time
     - Bar charts: Sales & Profit by Category and Region
   - Screenshot saved as `dashboard.png`

## Key Insights & Recommendations
- **Strongest revenue drivers**: Technology and Office Supplies categories
- **Regional performance**: West leads sales, but Central needs margin improvement
- **Seasonality**: Clear Q4 peaks — holiday-driven
- **Recommendations**:
  - Prioritize inventory and marketing for top-performing products (especially Technology)
  - Reduce aggressive discounting in low-profit regions to protect margins
  - Plan promotions and stock around seasonal peaks (Q4)
  - Explore opportunities to lift underperforming categories/regions

## Learnings
- Excel pivot tables + slicers are powerful for creating client-ready interactive dashboards
- Turning raw sales data into actionable business recommendations is the real value

## How to View the Work
- View the dashboard screenshot: `dashboard.png`
- To replicate: Download the original Kaggle dataset and build similar pivots/slicers in Excel

**Submitted as part of Future Interns – Data Science & Analytics Internship (Task 1 – 2026)**