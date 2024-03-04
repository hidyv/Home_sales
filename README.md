# Homes_sales

## Purpose 

 * Use SparkSQL to determine key metrics about home sales data.
 * Spark is used to create temperory views, partition of Data, Cache and uncache a temperory table.
 * compare running time of a query with original CSV data, data in cached temperory file and the data in Parquet format

## Metrics of home sales data

The following were answered by using SparkSQL:

* What is the average price for a four-bedroom house sold for each year? Round off the answer to two decimal places.

* What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? 

* What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?  

* What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query?.