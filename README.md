# Home Sales Query using SparkSQL

For this project, I used PySpark, and SparkSQL on Google Colab to determine key metrics about home sales data. Using Spark, I could create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.


## Overview

* Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

* Import the necessary PySpark SQL functions for this project.

* Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

* Create a temporary table called home_sales.

    * Answer the following questions using SparkSQL:

        * What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

        * What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

        * What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

        * What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

* Cache the temporary table home_sales.

* Verify that the temporary table is cached.

* Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to the uncached runtime.

* Partition by the "date_built" field on the formatted parquet home sales data.

* Create a temporary table for the parquet data.

* Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to the uncached runtime.

* Uncache the home_sales temporary table.

* Verify that the home_sales temporary table is uncached using PySpark.
