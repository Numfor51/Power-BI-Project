# 1.0 INTRODUCTION

In the world of rapid changing technologies and innovation, business intelligence and data analytics is becoming inevitable in business management and decision making by managers of organizations.
Data analysis as we might have seen is a broad term with a range of techniques or platforms or softwares that can help reveal delightful or meaningful insights, trends and relationships that may exist within raw business or organizational data. Power BI lends itself and fits readily well as one of such business tools or softwares for oragnizational data analysis. Power BI allows you to create your own reports, run queries, or analyze data, then build interactive data visualization dashboards and analytics. You can then use your key insights or findings to make recommendations to managers to be able to make meaningful business decisions, improve performance and procedures, and also make predictions for future occurences.  

In this project, we will be using Power BI to analyze and visualize data for a product supply company for 2016 to 2017 fiscal years. The dataset is gotten from kaggle.com.

## 1.1 Aim of Project:
At the end of this product, we hope to the achive the following
⦁	Learn how you can use Power Bi for data analysis and visualization.

⦁	Understand the steps involved in handling and analysing data or in order words, understand the different stages of a data analysis workflow

# 2.0 BACKGROUND AND METHODOLOGY

It is worthy to mention that the process of Data Analysis is very broad and complex. Depending on which specific objectives you hope to achive, or on which dataset you are working with, it will necssitate you to have the right approach or protocol in performing your analysis. Having the right analytical strategy or approach to follow is what is call data analysis workflow.
So to say, a data analysis workflow is a process consisting of a set of steps to follow when analyzing data. Usinig a workflow allows everyone involved to know what next would happen as the project progresses. 
Also, it will help as a guide to your methodology. Using a workflow minimizes time and errors. It also helps in work or data reproducibility and scalability. 
It is also good to mention here that there is no single rigid workflow or a universal data analyss workflow framework that satisfies all analysis or pojects. However, as a general rule, the workflow diagram below could be a good guideline in your data analysis project. 
![workflow](https://github.com/Numfor51/Power-BI-Project/assets/173632337/688bfd6c-85a9-4f85-9c20-7cf38843e9de)

Figure:1.0. A Data Analysis Workflow

This structure will then serve as a methodology or approach that will guide us complete and attend the objectives of our project. 

## 2.1 Tools/Material:
⦁	Power BI will be the main tool for our analysis and visualization.

# 3.0 OBJECTIVES

### Main Objective:
⦁	The main objective of this project is to gain experience in Data Analysis and visualization using Power BI.
### Specific Objectives:
⦁	To analzye the data and produce visual dashboards using Power BI.
⦁	What key performance indicators could be gotten from the data.
⦁	To identify important insightd, trends, predictions and recommendations to stakeholders.

# 4.0 DATA ACQUISITION

The data for this project was gotten from kaggle.com.

# 5.0 DATA EXPLORATION

The data gotten is raw data with a variety of tables and information to understand. Looking at the data, it is evident that we won’t be needing all of it to meet ourt objectives. As such we collected only the files that are necessary for our objectives into Power BI. We decided to work with 7 tables or datasets, namely; customer datateset, delivery dataset, orders dataset, products dataset, payments dataset, Sellers dataset and Reviews Dataset.
In data exploration, we are trying to understand the structure and attributes of the dataset.
These datasets collectively provide insights into different aspects of the business operations, customer interactions, and product/service performance.
In Power BI (PBI), these datasets can be used to analyze various aspects of a business's performance and operations as mentioned below; 
## 5.1. customer_dataset: 
It gives information about customers, with tables including;
⦁	Customer ID: A unique identification code assigned to the customer
⦁	Customer City: City where the customer lives
⦁	Customer State: State where the customer lives
⦁	Customer zipcode: zipcode of the exact state
Here we can analyze customer demographics and customer segmentations based on order behaviours.
## 5.2. Delivery_status_dataset: 
This Dataset is related to information about deliveries, such as; 
⦁	Order ID: A unique identification code assigned to eah order made.
⦁	Order delivery status: e.g., invoiced, shipped, delivered, cancelled, processing, unavailable. 
⦁	Order delivery carrier date: When shipment was picked up for delivery.
⦁	Order delivery estimated date: The date the order was estimated to be delivered.
⦁	Order delivered to customer date: The exact date the order was delivered to the customer. 
Here we can analyze;
-Delivery Performance: Track delivery times, delays, and success rates.
-Geographic Analysis: Map delivery performance across different regions.
-Delivery Trend Analysis: Identify trends in delivery times over various periods.
## 5.3 Orders_dataset: 
This dataset gives details about orders placed with information such as; 
⦁	Order ID: A unique identification code assigned to every order made.
⦁	Customer ID: A unique identification code assigned to the customer who made order.
⦁	Seller ID: A unique identification code assigned to the seller who sold the product.
⦁	Product ID: A unique identification code assigned to the product order.
⦁	Quantities ordered: The quantity of product that was ordered. 
⦁	Prices: The price per order. 
⦁	Order date: The date the order was made. 
⦁	Shipment date: The date the order was shipped.
⦁	Freight value: The cost of the shipment.
Here we can analyse,
Sales Performance: Monitor total sales, average order value, and order frequency.
Order Trends: Analyze order trends over time (daily, weekly, monthly).
Top Products: Identify best-selling products and categories.
## 5.4 Payment_mode_dataset: 
The dataset depicts information about the payment methods used by customers including; 
⦁	Order ID: A unique identification code assigned to the order made.
⦁	Payment types: Different payment types used by customers (such as credit card, debit card, voucher and boleto), 
⦁	Number of payment installments: The number of installments ot times that a customer made the total payment. 
⦁	Payment sequential: The priority or class assigned to the payment.
From this information, the following could be analyzed;
-Payment Methods: Visualizing the different payment methods used by customers.
-Payment Trends: Track changes in payment method preferences over time.
-Payment Method Performance: Compare the performance of different payment methods in terms of sales and customer satisfaction and also by different cities.
## 5.5. Products_dataset: 
The product Dataset shows information about the products offered by the business, including;
⦁	Product name or category name, 
⦁	Product ID: A unique identification code assigned to the product.
⦁	Product name length: Number of name characters
⦁	Product description length: How the product description is.
⦁	Number of product photos: Number of photos each product has.
⦁	Product weight(g): The actual eight of each product in grams.
⦁	Product length(cm): The length dimension of the product in cm.
⦁	Product height(cm): The height dimension of the product in cm.
⦁	Product width(cm): The width dimension of the product in cm
With this information, we can analyze the following insights;
 -Product Performance: Sales and profitability of individual products and categories.
 -Inventory Management: Monitor stock levels and predict inventory needs.
 -Product Trends: Identify emerging product trends and seasonality effects.
## 5.6 Reviews_dataset: 
It gives feedback and reviews provided by customers on products or services, including ratings, comments, and timestamps. This dataset includes the following tables; 
⦁	Review ID: A unique identification code assigned to the review.
⦁	Review Score: A numerical value assigned to the review.
⦁	Comment title: The title or subject of the comment.
⦁	Actual Comment: The full comment. 
⦁	Review creation date: Date review was submitted.
⦁	Review answered date: Date review was responded.
From the review dataset we can get insights like;
   - Customer Feedback: Analyze the level of satisfaction of customers and identify common trends.
   - Product Ratings: Visualize average ratings and review counts for products.
   - Customer Satisfaction: Correlate reviews with sales and delivery performance to gauge overall customer satisfaction.
## 5.7 Sellers_dataset: 
It shows information about sellers or vendors associated with the business, including contact details, product offerings, and possibly performance metrics. This dataset contains specific tables with; 
Seller ID and demographic information such as zipcode, city and state.
From here we can get information such as;
   - Seller Performance: based on sales, delivery times, and customer reviews.
   - Seller Comparison: Compare the performance of different sellers.
   - Product Listings: Analyze the range and quality of products offered by different sellers.

# 6.0 DATA TRANSFORMATION
The data was imported as a csv file into Power BI, transformed and loaded (ETL)

# 7.0 DATA CLEANING

### 1. Customer dataset:
⦁	Customer zip code table: Datatype was changed from numbers to text.
### 2. Delivery dataset: 
⦁	The columns were promoted such that the first-row entries became the column headers.
⦁	Order delivery carrier date table: 
            -Null values were found which were removed. However, this operation is unorthodox without the consent of the rest of the team. This was only done for the purpose of this project to ease the work for better understanding. So, the final report values may not be the same with others working on the same data. 
             -This table was split to have the date and the time as separate columns, then renamed
⦁	Order delivery customer date table: 
-Null values were found which were removed. Again, this operation is unorthodox without the consent of the rest of the team. This was only done for the purpose of this project to ease the work for better understanding. So, the final report values may not be the same with others working on the same data.
-This table was split to have the date and the time as separate columns, the renamed
⦁	Order estimated delivery date table: 
-This table was split to have the date and the time as separate columns but the time column was then deleted because the time was zero-zero.
-All the datatypes for the three date columns were text type and so they were all changed to date type. However, each of them threw error messages when changed to date type for reasons unknown but the error message indicated that there were errors in some values. The percentage error was indicated to be at least 60% for each column which really raised some concerns as to why this high error margin. However, for the sake of this project, and to have a clean workable dataset, it was deemed necessary to delete or remove the errors. Once this was done, everything was fine with the dataset but we lost about 60% of vital information which could be misleading and affect decision making for the business. In cases like these, this operation again is unorthodox to perform without the consent of the rest of the team or your company. As such the final report values may not be the same with others working on the same data if there do not face this problem.
### 3. Orders dataset:
⦁	The order_date and Ship_date table: These two tables had the dates joined with the time to appear like a datetime stamp. Equally, the datatypes were text instead of date type or date time stamp. Once the datatypes were changed to date time stamp, it threw errors. For this reason, the tables were split to have separate date and time tables, then later renamed. Again, when the date datatypes were changed to date type, it still threw errors. Checking the percentage error, it was found to be at least 35% for each column which really raised some concerns as to why this high error margin. However, for the sake of this project, and to have a clean workable dataset, it was deemed necessary to delete or remove the errors. Once this was done, everything was fine with the dataset but we lost about 60% of vital information which could be misleading and affect decision making for the business. In cases like these, this operation again is unorthodox to perform without the consent of the rest of the team or your company. As such the final report values may not be the same with others working on the same data if there do not face this problem.
### 4. Payment_mode_dataset: 
⦁	Everything seemed to be ok with this dataset so cleaning was not necessary.
### 5. Products_dataset:
⦁	Product_category_name table, Product_name_length table, Product description_length table, and Product_photos_qty table: These four tables were found to have null values of about 23% on average. The null values were removed. However, this operation is unorthodox without the consent of the rest of the team. This was only done for the purpose of this project to ease the work for better understanding. So, the final report values may not be the same with others working on the same data.
### 6. Reviews_dataset:
⦁	Review_comment_title table: From observing this table, it was found that only 12% of the review comments had titles. The rest were blanks or null values but it was deemed necessary not to remove blanks because some customers could actually send messages without titles.
⦁	Review_comment_message table:  It was observed that 56% of all products had review messages or were reviewed while 44% were blanks or not reviewed. Again, it was necessary not to remove the blanks because our interest is not to work only with products that have been reviewed.
⦁	Review_creation_date table and Review_answer_timestamp table: These tables were found to have a text datatype which was incorrect. However, when changed to their respective datatypes, it threw errors estimated to be as high as about 55% on average. For this reason, and to have a clean workable dataset, it was necessary to remove the errors event though downsizing the dataset. As such, the tables were split, then renamed, unnecessary columns removed, errors removed and given the right datatype. By doing this, everything works well for the dataset. However, this operation of removing errors or blanks must be done in consultation with the rest of the team because the operation is usually results misleading.
### 7. Sellers_dataset:
⦁	Seller_zip_code_prefix table: Here the datatype was changed from numbers to text. No further actions or cleaning was done on this dataset.

# 8.0 DATA ANALYSIS

By integrating these datasets in Power BI, you can create comprehensive dashboards and reports that provide a holistic view of the business, enable data-driven decision-making, and identify areas for improvement across various functions.
Analyzing the provided datasets in Power BI can address a variety of business questions, enhancing decision-making and operational efficiency. 

### 8.1 Key Insighs:
Here are specific business questions that can be answered using each dataset:
### 1. Customer_dataset:
⦁	Who are our most valuable customers?
⦁	What are the demographic characteristics of our customers?
⦁	How often do customers make repeat purchases?
⦁	How do different customer segments behave?
Segmenting customers based on purchase history, preferences, and demographics.

### 2. Delivery_status_dataset
⦁	What is our average delivery time?
⦁	Where do we experience the most delivery delays?
⦁	What are the common causes of delivery delays?
⦁	How does delivery performance vary by region or product type?

### 3. Orders_dataset
⦁	What are our sales or order trends over time?
⦁	Which products are our best-sellers?
⦁	What is the average order value?
⦁	How do order volumes fluctuate seasonally?

### 4. Payment_mode_dataset
⦁	Which payment methods are most popular among our customers?
⦁	Are there trends in payment method preferences over time?
⦁	How does payment method affect transaction completion and order value?
⦁	What is the rate of payment failures or issues by payment method?*

### 5. Products_dataset
⦁	Which products have the highest sales volumes?
⦁	How do product sales vary by category?
⦁	What are our inventory levels for each product?
⦁	How frequently do products go out of stock?

### 6. Reviews_dataset
⦁	What is the overall sentiment of customer reviews?
⦁	Which products receive the most positive or negative reviews?
⦁	What are common themes or issues mentioned in reviews?
⦁	How do reviews correlate with sales and returns?

### 7. Sellers_dataset
⦁	Who are our top-performing sellers?
⦁	How do different sellers compare in terms of delivery times and product quality?
⦁	What is the product range and diversity offered by each seller?

## 8.3 Data Analysis Expressions(DAX) Calculations.
### 8.3.1 Order Dataset:
⦁	New measure of Average Price, Total Price, Highest Price
⦁	New measure of Highest freight values, Total Freight value, Average Freight value
⦁	New measure of Highest Order quantity, Total Quantity order, Average order quantity.
⦁	New column showing; Average quantity ordered overtime(daily, weekly, monthly, quarterly, yearly)
⦁	New column showing; Total number of orders made overtime(daily, weekly, month, quarterly, yearly).
⦁	New colum showing shipment over time.
⦁	New column for Shipment time in days
⦁	New measure of Average shipment time in days
⦁	Date of last order, Date of last shipment
### 8.3.2 Delivery Dataset:
⦁	New measure of total deliveries
⦁	Total Deliveries by demographics
⦁	New calculated column for total deliveries over time(daily, weekly, month, quarterly, yearly)
⦁	New column to calculate delivery time in days.
⦁	New measure for average delivery time in days.
### 8.3.3 Payment dataset:
⦁	New measure; Average payment installment, Highest payment installment
⦁	New measure, average, sum, max, Payment installments by payment type and by states
8.3.4 Products Dataset:
⦁	New measures; average product weight, total product weight, max product weight.
⦁	New calculated column of product volume
⦁	New measure of total product volume, average product volume, max product volume.
⦁	New calculated column of product volume over time(daily, weekly, month, quarterly, yearly)
### 8.3.5 Customers Dataset:
⦁	New measure of total number of customers
⦁	Measure of the number of customers by demographics.
⦁	New calculated column of total number of customers over time (daily, weekly, month, quarterly, yearly)
⦁	Measure of most valuable customers based on product volumes
### 8.3.6 Sellers Dataset:
⦁	New measure of total number of sellers
⦁	New measure of the total number of sellers by demographics
⦁	Measure of most valuable sellers based on product volumes
### 8.3.7 Reviews Dataset:
⦁	New measure; average review score, total review score, max/min review score, date of last review.

# 8.4 Power BI Visualization Dashboards
## 8.4.1 General Performance Overview
 ![kpi](https://github.com/Numfor51/Power-BI-Project/assets/173632337/a7dea918-3660-4f4a-93a6-6aa15f4ce7b4)
### Key Insights:
⦁	We experience a 23% increase in the total number of orders in 2018(>17k orders) as opose to 2013(13k orders).
⦁	The average freight value in 2017 was 19.19 as opose to 20.48 in 2018, indictaing a percentage increase of a 6.3% in flight value.
⦁	The most preferred method of payment by cutomers across different states was Credit card.
## 8.4.2 Order Trends Analysis
 ![orders](https://github.com/Numfor51/Power-BI-Project/assets/173632337/03f5398f-5b5f-4e32-b544-5a4c0b3e506c)
### Key Insights:
⦁	We had gain of 1 day in the average shipment time. 101 days in 2018 as opose to 102 days in 2017. We noticed that most of the shipments were being on Saturdays.
⦁	It was noticed that most of our orders are being made on Thursday and most orders are made in the 3rd quarter of the year and precisely in the month of July
⦁	It is observed that most of our orders came from State SP(7336 orders) and the least from State RR(11 orders).

## 8.4.3 Product Trend Analysis
 ![prdts](https://github.com/Numfor51/Power-BI-Project/assets/173632337/770110fa-3d75-4a8c-a545-fc54bdfc36eb)
### Key Insights:
⦁	Our most and least valuable or selling products are the top 10 highest quantity order and first 10 from the bottom least selling products

## 8.4.4 Payment Trends Analysis
 ![paymt](https://github.com/Numfor51/Power-BI-Project/assets/173632337/09f9d2eb-401f-4e18-943d-29e44d8113e8)
### Key Insights:
⦁	The most preferred method of payment by cutomers across different states was Credit card.
⦁	The average number of payment installments was marked at 24 installments

## 8.4.5 Delivery Trends Analysis
 ![deliv](https://github.com/Numfor51/Power-BI-Project/assets/173632337/8f778748-a4c4-450f-a35a-57c5c24934bd)
### Key Insights:
⦁	We had remarkable successful gain in the average delivery time over the years. As long as 153days in 2016, and as low as 105days in 2017 and 95days in 2018. 
⦁	It was also observed that most of the deliveries are effected on Thursdays every week and in the month of November in the 4th quarter of the year.

## 8.4.6 Customer Trends Analysis
 ![custo](https://github.com/Numfor51/Power-BI-Project/assets/173632337/b1c770af-20b0-4e5c-b992-7e7ef057153d)
### Key Insights:
⦁	It can be observed that most of our most valuable customers are located in State SP.
⦁	The most expensive or the state with the highest freight value was State AC which the on the contrary one of the states with the list orders. On the one hand, the state with least average freight value was State SP which the state with our must valuable customers.

## 8.4.7 Seller Trends Analysis
 ![seller](https://github.com/Numfor51/Power-BI-Project/assets/173632337/0796925b-8f25-4bc1-8034-ea9f8588502a)
### Key Insights:
⦁	Most of our sellers are distribute in State SP and in the Soa Paulo city
⦁	Our top 10 must valuable sellers or sellers with the highest sales were considered to be those who have sell volumes > 200000units.

## 8.4.8 Review Trends Analysis
 ![review](https://github.com/Numfor51/Power-BI-Project/assets/173632337/3d0aa46e-0367-4c68-9c06-ff5153ec029a)
### Key Insights:
⦁	Products with highest reviews had a review score of at least 5

# 9.0 CONCLUSION AND RECOMMENDATIONS

⦁	It is recommended to maintain growth in all KPIs, such as freight value, price, revenue, payments, delivery time, shipment time, payment type. As such, the strategies implemented by various stakeholders and departments should align with these objective and should be strickly respected by cross functional teams.
⦁	It is recommended to have a continuous review of shipment and delivery routes to the best interest of the company to have a reduction in the average delivery  and shipment time, to minimize cost and maintain customer satisfaction.  I therefore suggest that highly efficient routes which are less costly should be maintain while reviewing other routes. This is so because we have noticed that the state with the highest average freight value was the state with the least number of orders sold. Routes like these are advisable to reduce resource pull.
⦁	It is advisable that the customers and states with highest number of orders should be motivated with bonuses or gratifications and those with least orders, we should increase promotions and publicity.
⦁	It is also advisable that most resources in least functional routes should be reduced and relocated to highly functional or profitable routes.
⦁	To my opinion, the average payment installments of 24 installments is too high. Measures should be taken to reduce the payment time or number of installments.
⦁	It is of interest to inverst more in our top selling products such as increase in stock and promotions such that they hardly run out of inventory.
⦁	It is equally advisable to continuously motivate our most valuable sellers with incentives, bonuses for them to increase our sales volume and yield more returns in revenue and profit.
⦁	Continuous rewiew analysis should be effect to always quickly identify customers satisfaction and dissatisfaction.
