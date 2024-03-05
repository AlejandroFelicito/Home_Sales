# Home_Sales
Module 22 Challenge


## Description 
**Home_Sales** solution, due 03/07/2024


## Before you begin 
1. Create a new repository for this project called **Home_Sales**. Do not add this homework to an existing repository.
2. Clone the new repository to your computer.
3. Push your changes to GitHub.


## Instructions 
1. Rename the _Home_Sales_starter_code.ipynb_ file as _Home_Sales.ipynb_.
2. Import the necessary PySpark SQL functions for this assignment.
3. Read the _home_sales_revised.csv_ data in the starter code into a Spark DataFrame.
4. Create a temporary table called `home_sales`.
5. Answer the following questions using SparkSQL:
    * What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
    * What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
    * What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
    * What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
6. Cache your temporary table `home_sales`.
7. Check if your temporary table is cached.
8. Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
9. Partition by the "date_built" field on the formatted parquet home sales data.
10. Create a temporary table for the parquet data.
11. Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
12. Uncache the `home_sales` temporary table.
13. Verify that the `home_sales` temporary table is uncached using PySpark.
14. Download your _Home_Sales.ipynb_ file and upload it into your "Home_Sales" GitHub repository.

## Submission 
To submit your Challenge assignment, click Submit, and then provide the URL of your GitHub repository for grading.


## Credits 
* Received comments and guidance from Instructor, Teaching Assistant 
* Used StackOverflow and module documentation for specific details