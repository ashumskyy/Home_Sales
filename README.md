# Home_Sales

This project analysing the home sales data of years 2010-2017. 
We created few queries of the data frame, then we cached the df and also we partitioned the data on the formatted parquet. At every stage we checked the runtime. 

## Steps

1. Import the necessary PySpark SQL functions for this assignment.
2. Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.
3. Create a temporary table called home_sales.

4. 
### Queries 

 - What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
 - What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
 - What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
 - What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

5. Cache temporary table sales_view.
6. Check if temporary table is cached.
7. With the cached data, we run the last query. Show the runtime and compare it to uncached runtime.
8. Partition by the "date_built" field on the formatted parquet home sales data.
9. Create a temporary table for the parquet data.
10. Run the last query. Show the runtime and compare it to uncached runtime.
11. Uncache the sales_view temporary table.
12. Verify that the sales_view temporary table is uncached using PySpark.
