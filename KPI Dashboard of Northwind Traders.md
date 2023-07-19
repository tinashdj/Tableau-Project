**Project Brief**

Northwind Traders is a global import and export company that specializes in supplying high-quality gourmet food products to restaurants, cafes, and specialty food retailers around the world.
The goal of this project is to build a top-level KPI dashboard to help Northwind Traders' executives quickly understand the company's performance in key areas, including Sales trends, Product performance, Key customers and Shipping costs

**About The Data Set**

Sales & order data for Northwind Traders, a fictitious gourmet food supplier, including information on customers, products, orders, shippers, and employees. This dataset provides data from July 2013 to May 2015.

Dashboard link: https://public.tableau.com/app/profile/sri.hartina/viz/KPI_Traders/Dashboard1#1

![KPI Dashboard of Northwind Traders](https://github.com/tinashdj/Tableau-Project/assets/110084624/c16a9b88-3b80-4fab-8d06-d590b04bdc79)


**The Concept**

In this project I only use a single page dashboard to shows the KPI performance.
The executive team is likely interested in the current reporting period (month, quarter, year) and how the company is trending from previous periods. Providing details on what was happening 2-3 years ago is probably irrelevant unless there is some cyclic trend.

I omitted the "live data" from the month of May 2015, because that May 2015 wasn't a complete month. I focused on the Reporting Month (RM) and Reporting Year (RY). The RM was the previous complete month (April 2015) and the RY was the year to date for 2015 (Jan, Feb, Mar, Apr).

Then to give the user more context, I provide additional calculation information to show the month over month change percentage of the previous month.
There is additional information in the tooltip on some visuals to provide detailed information that is not shown on the visual chart. Hover for tooltip on reading visual.

**Key Reporting Areas**

**Revenue**

The line chart of “Revenue by Month” shows the revenue trend from January to April in 2015. The “Total Revenue” is the total revenue in 2015. The “Month over Month (MoM)” is the percentage difference of revenue from March 2015 to April 2015, and its show that the revenue trend is increasing. Click the tooltip to see the revenue from previous month.

The line chart of “Order by Month” shows the total order trend from January to April in 2015 and the “Total Order” is the total order that was ordered in 2015.

**Customers**

The “Top Customer” show the top customer based on the revenue in April 2015. The bar chart of “Save-a-lot Markets by Month” show the difference month revenue of Save-a-lot Markets from January 2015 to April 2015. The “Top 3 Customers in Apr,15” show the top 3 customers in April based on the revenue. Hover for tooltip on reading visual to see the city and country of the customer. The “Month over Month (MoM)” is the percentage difference of Save-a-lot Markets revenue from March 2015 to April 2015, and its show that the Save-a-lot Markets revenue trend is increasing. Hover for tooltip on reading visual to see the revenue from previous month.

The line chart of “Customers by Month” shows the total customers trend that ordered from January to April in 2015 and the “Total Customers” is the total customer that ordered in 2015.

**Products**

The “Top Product” shows the top product based on the revenue in April 2015. The bar chart of “Raclette Courdavault by Month” shows the difference month revenue of Raclette Courdavault from January 2015 to April 2015. The “Top 3 Products in Apr,15” shows the top 3 products in April based on the revenue. Hover for tooltip on reading visual to see the category of the products. The “Month over Month (MoM)” is the percentage difference of Raclette Courdavault revenue from March 2015 to April 2015, and its show that the Raclette Courdavault revenue trend is increasing. Hover for tooltip on reading visual to see the revenue from previous month.

The line chart of “Products by Month” shows the total products trend that was ordered from January to April in 2015 and the “Total Products” is the total product that was ordered in 2015.

**Shipping**

The line chart of “Freight Cost by Month” shows the total freight cost trend from January to April in 2015 and the “Total Freight Cost” is the total freight cost in 2015.

The doughnut chart of “On-Time Delivery” shows the difference percentage between on-time and late delivery in 2015. The bar chart of “Avg. Freight Cost Per Order” shows the average freight cost per order based on shipper name in 2015. 
