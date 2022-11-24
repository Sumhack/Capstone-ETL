##Overview

U F H
Its an ecommerce company dealing in organic groceries.
They are still an early stage startup. They operate in 20 Cities in India at this moment accross 6 States. They promise to deliver the order within 48 hours after order placement. They offer 50 different type of products in different SKUs.
At this moment they recieve between 500-1000 orders per day across India. 
They soon plan to expand their capabilities to serve between 10000 to 20000 orders per day.




##TASKS

Create tables as defined in  OLTP Schema in Cloud SQL PostgreSQL. Make sure you have repeatble scripts to create tables again and again
Populate the tables in Step 1 using Python Faker library. Make sure Data follows primary and foreign key constraints
At minimum Need 1000 unique customers, 120 unique dates, 20000 orders, 20 cities, 50 Products each with minimum 2 SKUs
Create tables defined in STAR Schema in BigQuery. Make sure you have repeatable scripts to create tables again and again
Write ETL to load data from OLTP to STAR Schema using Python, BigQuery & Composer
Make sure you take care of one time load and incremental load
Use your code in step to generate new 5000 orders and populate OLTP schema
Run your incremental ETL to load Data about additional 5000 orders
Write BigQuery SQL for each of the analytics requirements (10) to generate reports


##Analytics Requirements

Average number of items per order - daily, monthly, weekly, state, city, pincode
Average amount of sales per order -  daily, monthly, weekly, state, city, pincode
total number of units sold per day of a product SKU and its monthly trend
Total Order Amount on daily basis, also to be able to split by product and geography
Distribution of orders according to area ( state, city, pincode etc)
Average order amount per customer on daily basis
New Customers on daily basis
Total count of customers everyday
Average time to delivery order. Min and Max time. To be able to slice and dice on hour, weekday, weekend, daily, monthly, geography, 
Total orders : to be able to slice and dice on hour, weekday, weekend, daily, monthly, geography


