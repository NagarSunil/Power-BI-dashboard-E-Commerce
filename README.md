# Power-BI-dashboard-E-Commerce
E-Commerce Power BI 

Dashboard 1 - E-COMMERCE Revenue Dashboard

This dashboard effectively combines various visualization types and KPIs to provide a comprehensive view of the e-commerce performance, making it a valuable tool for decision-makers.


 - KPI's Used:-
1) Total Revenue Purchase (Value 5.65 M) - Created Measure by adding all the products from sales table that are purchased after promotion and non-promotion

2) Non-Promotion Revenue - (Value 4.47 M) - The revenue generated from purchases without any promotions. Created Measure and calculated Non_Promo_Revenue.

3) Total Promo Revenue (Value 1.18 M) - The revenue generated from purchases with promotions applied. Created Measure and calculated Total_Promo_Revenue.

4) Average Event Hour (Value 11.09 Hr) - The average hour of the day when events (like purchases) occur. Created Measure and calculated Avg_Event_Hour.

5) Average Discount (Value 15.05%) - The average discount percentage applied to purchases by promoting the products. Created Measure and calculated Avg_Discount


- Chart Types and Analysis :-

1) Purchased Product Revenue by Category - BAR CHART
* Displays the revenue generated from different product categories.
a) Electronics category generates the highest revenue, indicating a strong customer preference or higher pricing in this category.

b) Categories like Appliances and Computers generate significantly lower revenue, suggesting potential areas for marketing focus or product improvement.

2) Purchased Product Revenue and User Activity by Event Hour - LINE and CLUSTERED COLUMN COMBO CHART
* Combines a bar chart and line chart to show the revenue and user activity by hour of the day.
a) Revenue and user activity peak between 10 AM and 4 PM, suggesting these are the most active shopping hours.
b) There is a gradual decline in both revenue and user activity post 4 PM, with the lowest activity during late-night hours.

3) Revenue Distribution by Week by Day of Week - PIE CHART
*  Shows the distribution of revenue across different days of the week.
a) Sunday generates the highest revenue, followed by Monday, indicating higher sales during weekends and the beginning of the week.
b) Midweek days (Tuesday to Thursday) generate relatively lower revenue, which might indicate a typical trend of lower midweek shopping activity.

SLICERS
1) Channel: Filter data by the channel used (App, Browser).
2) Brand: Filter data by specific brands (Acer, Apple, Arg, etc.).
3) Day of Week: Filter data by specific days of the week (Friday, Monday, Saturday, Sunday).


Dashboard 2 - USER ACTIVITY 

This dashboard provides a comprehensive view of e-commerce performance with a focus on user activity, revenue, and transactions. The combination of bar charts, pie charts, tree maps, and combo charts allows for detailed analysis across various dimensions. 

1) User Activity by Day of Week - Clustered Column Chart
* Displays the total user activity for each day of the week.
a) Highest user activity is on Friday and Saturday.
b) User activity decreases towards the beginning of the week, with Monday showing the lowest activity.

2) User Activity by Channel - PIE CHART
* Shows the distribution of user activity between different channels (Browser and App).
a) User activity is almost evenly split between Browser (50.12%) and App (49.88%).

3) User Activity, Total Revenue Purchase, and Total Transactions by State and Brand - TREE MAP
* Visual representation of user activity, revenue, and transactions distributed by state and brand.
a) Different states show varying levels of activity and revenue for different brands.
b) Larger blocks represent higher activity and revenue, with prominent brands like Apple, Samsung, and Xiaomi in multiple states.

4) Total Revenue Purchase, User Activity, Total Promo Revenue, and Non Promo Revenue by Brand - LINE AND CLUSTERED COLUMN COMBO CHART
* Combines total revenue purchase, user activity, total promo revenue, and non-promo revenue for each brand.
a) Apple generates the highest revenue and user activity, indicating strong brand performance.
b) Other brands like Samsung and Xiaomi also show significant activity and revenue.
c) The line chart for user activity shows peaks for major brands, correlating with revenue data.


DASHBOARD 3 - PRODUCTS BIFURCATION across PURCHASE, VIEWED & CART products BY USERS

This dashboard effectively presents key performance indicators related to product transactions, user activity, and product views and carts by category.

1) Total Transactions by Month - STACKED COLUMN CHART
* Displays the total number of transactions for each month.
a) Transactions peak in November and December, indicating higher sales during these months, likely due to holiday season promotions.

2) User Activity and Viewed Product Count by Category - STACKED COLUMN CHART 
* Shows user activity alongside the count of products viewed by category.
a) Electronics have the highest user activity and product views.
b) Appliances and Computers also show significant user activity and views.

3) User Activity, Purchased Product Count, and Total Revenue Purchase by Category - STACKED COLUMN CHART
* Illustrates user activity, the count of purchased products, and total revenue by category.
a) Electronics lead in user activity and purchases, contributing significantly to total revenue.
b) Appliances show high user activity but lower purchases compared to Electronics.

4) User Activity and Cart Product Count by Category - STACKED COLUMN CHART
* Represents user activity and the count of products added to the cart by category.
a) Electronics and Appliances have the highest cart additions.
b) Categories like Computers and Furniture have lower cart activity.


DASHBOARD 4 - GEOGRAPHICAL MAPPING

The Power BI dashboard uses various KPIs and charts to present insights into brand performance, seasonal trends, and geographical distribution. The bar chart shows Samsung and Apple as leaders in state count and revenue. A combo chart reveals a significant spike in transactions and revenue during November and December, highlighting holiday shopping impact. An area chart illustrates transaction and revenue distribution across states, with MD, WV, and DC having high transactions, while CA, PA, and IL show higher average purchase values. The dashboard effectively uses different visualizations to convey key business metrics and trends.

1) Count of State and Purchased_Product_Revenue by Brand - Bar Chart
* Displays the Purchase of Brands and generated revenue across total count of states
a) The chart shows that Samsung and Apple dominate the market in terms of state count and product revenue.
	- Samsung has the highest count of states and purchased product revenue.
	- Apple follows closely in both metrics.
	- Xiaomi, Huawei, and LG are other notable brands with significant counts and revenue.
b) There is a diverse range of brands, but the top few brands account for a large share of the market.

2) Total_Transactions and Total_Revenue_Purchase by Month - LINE AND STACKED COLUMN COMBO CHART
* Shows volume of transactions and generated revenue across different months time period
a) Transactions and revenue remain steady from January to September.
b) A sharp increase in transactions and revenue in November and December indicates a strong holiday sales season.

3) Total_Transactions and Purchased_Product_Revenue by State - AREA CHART
* Shows volume of transactions and generated revenue across different states demographic
a) States with the highest transactions include MD, WV, DC, AL, and OR.
b) States like CA, PA, and IL show higher revenue despite lower transactions, indicating higher average purchase values.

