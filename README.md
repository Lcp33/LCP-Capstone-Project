**Description of Dataset**

The dataset is from a project for Shopee, Brazil. The data are from 4 countries namely Brazil, Chile, Columbia and Mexico. There are 2 main sets of data – customer and purchase. They consist of basic information of customers (name, country, age and income), the types of products purchased, quantity and shipping date and cost. The dataset has a size of 50,000 rows for “purchase” and 1,000 rows for “customer”. The dataset is dated from 2019 to 2023.
Some assumptions made on the dataset:
1.	Income = Annual income
2.	Price = Selling price per unit

**Description of Dashboard**

•	The Clustered bar chart shows total sales by country.
•	The Filled Map Chart shows the number of customers by country.
•	The Donut Chart depicts total sales by gender.
•	The Clustered Column chart shows total sales by Age group and Country.
•	The Clustered Column chart shows total sales by Income and Country.
•	The Line Chart shows the trend over time of sales by year, month and quarter.
•	The Treemap Chart displays hierarchical view of sales by products, showing buying patterns.
•	There are 2 slicers: Order Date and type of product. If the dashboard gives us a macro picture, the slicers helps us zoom into the individual units.

--

**Data Transformation**

Added columns to group the income and age.
Formatted text under order date from text to date.
Added columns to determine sales.
Formatted text under the price columns to currency ($).
