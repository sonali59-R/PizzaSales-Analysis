#  Pizza Sales Analysis Dashboard (MySQL + Power BI)

This project analyzes the sales performance of a fictional pizza restaurant chain using MySQL for data querying and analysis and Power BI for interactive dashboard visualization. The analysis uncovers key insights related to revenue trends, order patterns, customer preferences, and product performance.

The dataset consists of four relational tables:

orders – captures order-level information such as order ID, date, and time

order_details – stores item-level details including quantity and pizza IDs

pizzas – contains pricing and size information for each pizza

pizza_types – provides pizza names, categories, and ingredient details

These tables were joined using SQL to answer real-world business problem statements, such as:

 Total revenue generated and revenue trends over time
 
 Most popular pizza categories and sizes
 
 Best- and worst-performing pizzas by sales and quantity
 
 Peak ordering hours and daily order patterns
 
 Contribution of each pizza type to overall revenue

##  Tools & Techniques

MySQL – For data extraction and transformation  
Power BI – For data modeling, visualization, and dashboard design  
DAX Measures – Used for dynamic KPIs and variance calculations  
Conditional Formatting – Dynamic bar coloring for performance analysis  
Calendar Filtering – Used for date-wise trend exploration  

## Dashboard Features

### Page 1 – Overall Sales Overview
 Key metrics: Total Orders, Revenue, Units Sold, Avg. Orders per Day,MOM growth for orders,MOM growth for Revenue,MOM growth for Units
 Monthly trend line of orders, revenue, and units
 Revenue breakdown by:
  Pizza size 
 Pizza category
 Top 5 pizzas by revenue
  Day of week & hour heatmap (for staffing insights)

###  Page 2 – Product-Level Performance
- Table with:
  - ProductName
  - Total Orders
  - Revenue
  - Qty
  - Revenue Variance vs Target  with conditional formating 
- Donut chart showing product mix by category
- Revenue vs Avg revenue trend by order_date


##  Key Insights

 Most revenue comes from Large and Medium pizzas.
 **Chicken** and **Supreme** categories have the highest variety.
 Top performers:  
   The California Chicken Pizza  
   The Barbecue Chicken Pizza  
  Sales are significantly higher on WeekDays than on Weekends and between 12 pm to 8 pm
  Variance analysis identifies pizzas that underperform (great for promotions).

 

##  Dashboard Preview

pizza Dashbord -Summery (pizza_sale1.png)
pizza details- details(pizza_sales2.png)


##  Dataset Source

Kaggle - Pizza sales 48k+ rows



## Author

**Sonali Rajgure**  
Self-driven data enthusiast, focused on learning through real-world projects.  
🔗 [LinkedIn](https://www.linkedin.com/sonalirajgure)




