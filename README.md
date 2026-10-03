# Customer Sales Analysis with Python

## Project Overview

This project analyzes customer sales data using Python to evaluate business performance, customer purchasing behavior, product profitability, and sales trends.

The analysis includes data cleaning and validation, exploratory data analysis, customer and product analysis, time-based analysis, data visualization, and business recommendations.

## Tools Used

- Python
- pandas
- Matplotlib
- Jupyter Notebook

## Data Cleaning

The dataset required several cleaning and validation steps before analysis:

- Removed duplicate records
- Converted order dates to datetime format
- Identified and handled missing values
- Reconstructed missing Sales values using Cost and Profit after validating the relationship between the fields
- Filled missing customer names using existing Customer ID relationships
- Filled missing regions using existing State-to-Region relationships
- Standardized inconsistent Segment and Sales Channel values
- Validated the cleaned dataset before beginning analysis

After cleaning, the dataset contained 850 records.

## Analysis Performed

The analysis examined:

- Overall sales and profitability
- Category and product performance
- Customer segment performance
- Regional performance
- Sales channel performance
- Customer purchasing behavior
- Average order value
- Discount levels and profitability
- Monthly sales and profit trends
- Product-level sales and profit relationships

## Key Findings

- The business generated approximately USD 619K in sales and USD 181.8K in profit, with an overall profit margin of approximately 29.4%.
- Technology generated the highest category sales and profit, while Office Supplies achieved the highest category profit margin.
- Furniture had the lowest category profit margin, with Filing Cabinets, Conference Tables, and Bookcases among the lowest-margin products.
- Consumer was the largest customer segment by sales and profit, while margins remained relatively consistent across customer segments.
- The South generated the highest regional sales and profit, while regional profit margins differed by less than one percentage point.
- Online generated the highest sales and total profit among sales channels, while margins remained relatively consistent across channels.
- August was the strongest month for both sales and profit, while May recorded the lowest sales and profit.
- Discount levels did not show a clear relationship with profit margins. Product-level average discount and profit margin had only a weak correlation of approximately +0.20.
- CUST-0031 Maya Martinez generated the highest total sales and profit, supported by 10 orders.
- Several customers with high average order values had only one purchase, demonstrating why AOV should be evaluated alongside order frequency.

## Business Recommendations

1. **Investigate Furniture Profitability**  
   Examine the factors contributing to Furniture's lower profit margin, particularly for Filing Cabinets, Conference Tables, and Bookcases. Compare product costs, pricing, and other profitability drivers with higher-margin categories.

2. **Investigate the August Performance Peak**  
   Analyze product mix, pricing, costs, and possible seasonal factors behind August's strong sales and profit performance to determine whether similar strategies or timing could improve other periods.

3. **Analyze Repeat and One-Time High-Value Customers**  
   Evaluate repeat high-value customers separately from one-time high-AOV customers. Compare product mix, order timing, pricing, and profitability to better understand repeat purchasing behavior.

4. **Evaluate Discounts at the Product Level**  
   Avoid broad discount changes based solely on profit margin. Since the analysis did not show a consistent decline in margins as discounts increased, evaluate discounts alongside product-level pricing, costs, sales volume, and profitability.

## Visualizations

The project includes visualizations for:

- Monthly Sales
- Monthly Profit
- Sales by Category
- Lowest Profit Margin Products
- Product Sales vs. Profit

## Project Files

- `Customer_Sales_Analysis.ipynb` — Complete Python analysis
- `Customer_Sales_Python_Portfolio.csv` — Original dataset
- `Customer_Sales_Cleaned.csv` — Cleaned dataset used for analysis

## Conclusion

The business remained profitable throughout 2025, with relatively consistent profitability across customer segments, regions, sales channels, and months. The analysis identified opportunities for deeper investigation, particularly around Furniture's lower profit margins and the factors contributing to August's strong performance. Understanding these differences can support more informed product, pricing, and sales decisions.
