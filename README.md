# Sale-insights project
## project objective
This project focuses on analyzing sales data and building a one-page dashboard to visualize key sales insights. The analysis involves data gathering, modeling, DAX calculations, and visualization using Power BI.

## Dataset used
- <a href ="https://github.com/arunsaimuddu/Sale-insights/blob/main/Sale%20insight%20zip%20file.zip" >Data set</a>

## Questions (KPIS)
1. Consolidate all sales files into a single Sales fact table and transform the Sales fact table by splitting Country, City from the "Location" field.
2. Create unique key (GeoKey) in Sales and Geography table.
3. Create the Data Model connecting all tables and using the Calendar table already set up in the pbix.
4. Calculate Total Revenue in Sales table, using the Product’s Retail Price, and multiplying it by the Units.
5. Calculate Total Cost in Sales table, using the Product’s Standard Cost, and multiplying it by the Units.
6. Calculate Gross Profit in Sales: Total Revenue – Total Cost.
7. Calculate a Gross profit MoM growth Change% measure that could benefit us in decision making.
8. Calculate a measure for AVG sales per day – this is the average sum of Total Revenue per day based on the Dates of actual Sales.

## Dashboard view
- <a href ="https://github.com/arunsaimuddu/Sale-insights/blob/main/sales%20analytics%20report.pdf" >View report</a>

## Project insights 
1. The dashboard provides a clear view of revenue, cost, and profit trends, helping identify seasonal fluctuations and sales growth opportunities.
2.Regional & Product Insights – By splitting Country and City data, the analysis enables better geographical sales tracking, along with performance breakdowns for top-selling and underperforming products.
3.Data Quality & Transformation – Cleaning ID fields, ensuring proper date formats, and creating a GeoKey improve data accuracy and enhance model relationships for better decision-making.
4.Sales Efficiency & Opportunity Management – The model helps assess cross-sell, renewals, and new sales while identifying opportunities to optimize sales strategies.
5.Financial Performance Analysis – With MoM Growth %, QoQ Growth, and Avg. Sales per Day calculations, businesses can track profitability trends and make data-driven decisions.

## Project conclusion
1. The analysis provides a comprehensive understanding of sales performance, helping identify trends, high-performing products, and underperforming segments.
2. The automated data-loading mechanism ensures that new data is seamlessly integrated, making the model adaptable for future expansions.
3. The Cleaning and transforming data (e.g., ID formatting, date standardization, and unique GeoKey creation) ensures accurate reporting and reliable insights.
4. The insights highlight opportunities for cross-selling, renewal improvements, and optimizing sales efforts in specific categories, ultimately driving revenue growth.
