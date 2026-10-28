# Power-BI-assignment-2-Dax-Visualization
Dax Visualisation
# Power BI Assignment 2 – DAX & Data Visualization
Category Type:Combines Category and Sub-Category into one column.
Revenue per Order:Calculates revenue by multiplying Amount by Quantity.
Sales Category:Categorizes sales as Above Average or Below Average.
Order Count = DISTINCTCOUNT('Order Details'[Order ID])
YTD Sales=TOTALYTD([Total Sales], 'Calendar'[Date])
Total Sales=SUM('Order Details'[Amount])
Total Target=SUM('Sales target'[Target])
Minimum Target=MIN('Sales target'[Target])
Data Visualizations
Sales Target Achievement by Category:Clustered column chart comparing actual sales and targets by category.
Maximum Profit Margin by Sub-Category:Donut chart displaying the maximum profit margin for each sub-category.
Monthly Sales Trend:Line chart showing monthly sales trends in chronological order.
Profit and Quantity Comparison:Scatter chart comparing profit and quantity by sub-category.
Total Sales and Target Comparison:Card visuals showing total sales and total target, with a multi-row card showing minimum target by category.
Sales Performance Matrix:Matrix comparing actual sales and targets by category and month.
Geographic Sales Analysis:Map displaying total sales by city.
Sales Distribution by Sub-Category:Treemap showing sales distribution across sub-categories.
Order Count by State:Funnel chart showing order counts across states.
