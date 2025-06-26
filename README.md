# CHOCOLLY-CHOCOLATE-SALES-DATA-OVERVIEW-2022
![image](https://github.com/user-attachments/assets/f74b3a7a-3fed-4352-a163-4b0277b08535)


Introduction
This dataset captures sales transaction records, detailing the salesperson involved, country of sale, product sold, date of transaction, sales amount, and the number of boxes shipped. It provides valuable insights into sales performance, regional demand, and distribution efficiency. The primary aim is to analyze trends across products, locations, and time periods to support strategic sales and logistics decisions.



Data Preparation Procedure
Missing Data Handling
Checked for and addressed missing values in essential fields like Sales Person, Country, Product, and Amount.
Imputed or removed incomplete entries depending on data relevance.
Data Type Formatting
Converted Date to datetime format for proper time-series analysis.
Ensured Amount and Boxes Shipped are correctly typed as numerical values.
Standardization
Standardized text entries in fields like Country and Product to correct spelling variations or inconsistent casing (e.g., "usa" vs "USA").
Outlier Detection
Reviewed Amount and Boxes Shipped for unusually high or low values that could distort analysis.
Derived Fields (Optional)
Created additional features like Sales per Box (Amount ÷ Boxes Shipped) to assess efficiency and unit economics.



Independent Variables 
Sales Person
Country
Product
Date
Boxes Shipped

Dependent Variable 
Amount



Story of the Data
This dataset tracks the performance of chocolate product sales across different regions and by various sales representatives. Each record includes the country of sale, product sold, quantity in boxes shipped, sale date, and the resulting revenue amount. By analyzing this data, we aim to understand regional performance, product popularity, sales efficiency, and shipping dynamics. Insights from this data can help optimize operations, plan inventory, forecast demand, and improve sales strategies.



 Industry Type of Data
Fast Moving Consumer Goods FMCG
Subsector: Confectionery and Packaged Foods
 Stakeholders
Sales Managers
Marketing Team
Supply Chain and Logistics Team
Regional Managers
Financial Analysts
Retail Distributors
Executive Leadership
Product Development Team
Potential Insights
Top countries driving the highest chocolate revenue
Best performing sales person by revenue and volume
Clear seasonal spike in chocolate sales during specific months
Positive correlation between boxes shipped and revenue
Specific products perform significantly better in certain countries
Some sales reps perform better in specific regions
Low box-to-revenue ratio in certain countries indicates inefficiency



Potential Analysis Questions
Which sales person generated the highest revenue overall
Which country had the highest volume of chocolate sales
What is the correlation between boxes shipped and revenue
Are there seasonal trends in chocolate sales based on dates
Which product performs best in each country
How does performance vary between sales people
Are there underperforming products in specific regions
What is the average revenue per box shipped
Which countries show consistent growth or decline in sales
How does shipping quantity impact total sales value over time



Observations Board
1. Ches Bonnell is the Top Performer
Ches Bonnell is highlighted as the Best Sales Person, with a total amount sold of 0.32M, making them the highest contributor among all sales reps.
2. Peanut Butter Cubes is the Top Sold Product
Peanut Butter Cubes leads in sales, appearing as the Top Sold Product.
It ranks among the highest in the Sum of Amount by Product bar chart, at 0.32M.
3. Sales Were Consistent Throughout the Year
The Sum of Amount by Month line chart shows consistent fluctuations with peaks, notably around mid-June to July, suggesting stable demand throughout 2022.
4. Sales are Well Distributed Globally
Total Sales by Country reveals sales are spread across key markets including USA, UK, India, Australia, and Canada, each contributing significantly (~1M per country).
5. Top 3 Products Drive a Significant Portion of Sales
The top 3 products - Smooth Silky Salty, 50% Dark Bites, and White Choc - each contribute over 0.33M, highlighting a concentration of sales in a few SKUs.



Recommendations:
1. Launch a Performance Incentive for Top Sales Reps
Insight: Ches Bonnell and a few others contribute significantly to total revenue.
Action: Implement a rewards program and mentorship initiative to encourage high performers and uplift underperformers.
2. Expand Product Lines for Top Sellers
Insight: Peanut Butter Cubes, Smooth Silky Salty, and 50% Dark Bites are top earners.
Action: Introduce new flavors, sizes, or bundles under these product lines to increase repeat purchases and upselling.
3. Capitalize on Mid-Year Sales Peaks
Insight: Sales spike from June to July.
Action: Schedule product launches, special promotions, or limited-time offers around these months to maximize revenue.
4. Strengthen Sales in Emerging Markets
Insight: Countries like India, Canada, and New Zealand show nearly equal but lower contribution compared to top regions.
Action: Run targeted regional campaigns or partnerships in these areas to boost sales and brand visibility.
5. Balance Product Sales Across Categories
Insight: Few products dominate the revenue stream.
Action: Promote underperforming but promising products through seasonal bundles, discounts, or "Buy One Try One" offers to diversify revenue sources.



Conclusion
To drive sustained sales growth and market expansion, a focused and data-driven strategy is essential. Recognizing the outsized contributions of top-performing sales reps like Ches Bonnell, introducing performance incentives and mentorship programs can elevate the entire team's output. Expanding high-performing product lines such as Peanut Butter Cubes and Smooth Silky Salty will capitalize on existing consumer demand and encourage repeat purchases. Leveraging the consistent mid-year sales spike with targeted promotions can further boost revenue during peak periods. Additionally, investing in emerging markets like India, Canada, and New Zealand presents untapped growth opportunities. Lastly, promoting underperforming products through creative bundling and discount strategies will help balance revenue across the product portfolio and build a more resilient sales pipeline.
