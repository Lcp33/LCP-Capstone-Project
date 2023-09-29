![Image Alt Text](https://github.com/Lcp33/blob/main/Shopee1.png)

### Objective

Shopee is looking to create a customer base, improving customer experience and recommend relevant products to their customers and increase revenue. This report provides some important insights for the company to better understand their customers.

### Description of Dataset

The dataset is from a project for Shopee, Brazil. The data are from 4 countries namely Brazil, Chile, Columbia and Mexico. There are 2 main sets of data – customer and purchase. They consist of demographics of customers (name, country, age and income), the types of products purchased, quantity and shipping date and cost. The dataset has a size of 50,000 rows (6.65MB) for “purchase” and 1,000 rows(46.2KB) for “customer”. Both are CSV file type. The dataset is dated from 2019 to 2023.
Some assumptions made on the dataset:
1.	Income = Annual income
2.	Price = Selling price per unit


### Description of Dashboard

The Dashboard depicts that:
- The Clustered bar chart shows total sales by country.
- The Filled Map Chart shows the number of customers by country.
- The Donut Chart depicts total sales by gender.
- The Clustered Column chart shows total sales by Age group and Country.
- The Clustered Column chart shows total sales by Income and Country.
- The Line Chart shows the trend over time of sales by year, month and quarter.
- The Treemap Chart displays hierarchical view of sales by products, showing buying patterns.
- There are 2 slicers: Order Date and type of product. If the dashboard gives us a macro picture, the slicers helps us zoom into the individual units.

### General Observations

- Shopee Colombia has the highest total sales while Shopee Brazil has the lowest for the year 2019 to 2022.
- Shopee Colombia has the highest number of customers, while Shopee Mexico has the lowest.
- There are more Male (50.55%) customers than Female(49.45%).
- Among the four countries, the least no. of customer comes from Income below 25K. 
- Customers with income below 25k spend the least across four countries.
- The top 5 products sold are Curtains, Wall Art, Lighting, Furniture and Kitchen Appliance respectively.
- Sales trended up from July 2019 to May 2020, and stabilized till Nov 2022 and decline till Jan 2023.


### Data Transformation

- Added columns to group the income and age.
- Changed data type of order date from text to date.
- Added columns to determine sales.
- Changed data type of price columns from whole to currency ($).
