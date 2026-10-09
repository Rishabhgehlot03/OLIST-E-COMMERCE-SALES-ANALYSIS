# OLIST-E-COMMERCE-SALES-ANALYSIS

## 📂 Project Files & Resources

All project-related files, including the Power BI dashboard, SQL queries, Python notebooks, datasets, and project report, are available in the folder below.

📁 **[Access All Project Files]([PASTE_YOUR_FOLDER_LINK_HERE](https://drive.google.com/drive/folders/1r1v-DCs9t7RD21o0c6dAnbW1sKMzmPZj?usp=drive_link))**


An end-to-end data analytics project analyzing e-commerce performance across sales, customers, products, sellers, payments, reviews, and delivery using **Python, MySQL, SQL, Power BI, and DAX**.

## 📌 Project Overview

The Olist E-Commerce Data Analytics Project focuses on transforming raw e-commerce data into meaningful business insights through data cleaning, database modeling, SQL analysis, and interactive Power BI dashboards.

**Project Workflow:** Python → MySQL → SQL Business Analysis → Power BI & DAX → Interactive Dashboards

## 🎯 Problem Statement

E-commerce data is distributed across multiple tables containing information about orders, customers, products, sellers, payments, reviews, and locations. The raw data may contain missing values, duplicate records, inconsistent data types, and other issues that need to be addressed before analysis.

The objective of this project was to clean and organize the data, build a structured database, perform business analysis, and develop interactive dashboards to understand:

* Overall sales and revenue performance
* Customer and seller distribution
* Product and category performance
* Delivery efficiency
* Payment behavior
* Customer reviews and satisfaction

## 🛠️ Tools & Technologies

| Tool     | Purpose                                             |
| -------- | --------------------------------------------------- |
| Python   | Data cleaning, transformation, and feature creation |
| MySQL    | Database modeling and management                    |
| SQL      | Business analysis and KPI calculations              |
| Power BI | Data visualization and interactive dashboards       |
| DAX      | Measures and business KPIs                          |

## 🔄 Project Workflow

### 1. Data Cleaning Using Python

Python was used to prepare the raw Olist datasets for analysis.

Key activities:

* Checked missing values and duplicate records.
* Converted columns to appropriate data types.
* Handled missing product categories.
* Prepared date and time columns.
* Created analytical columns such as Order Year, Order Day, Delivery Days, and Delivery Status.
* Compared actual delivery dates with estimated delivery dates to determine delivery status.

### 2. MySQL Database Modeling

The cleaned datasets were structured in MySQL using tables related to:

* Customers
* Orders
* Order Items
* Products
* Product Categories
* Sellers
* Payments
* Reviews
* Geographical Information

Primary keys and foreign keys were used to establish relationships between the tables.

### 3. SQL Business Analysis

SQL queries were used to answer important business questions, including:

* What is the total revenue and average order price?
* How does revenue change over time?
* Which product categories generate the most revenue?
* How many customers and sellers are there?
* Which states have the most customers?
* Which sellers generate the highest revenue?
* What is the average delivery time?
* What percentage of orders are delivered early, on time, or late?
* Which payment types generate the most revenue?
* What are the average customer review scores?
* How do reviewed and non-reviewed customers compare?
* How does freight value vary by product category?

### 4. Power BI & DAX

The prepared data was imported into Power BI. Relationships between tables were configured, and DAX measures were created to calculate business KPIs and support interactive dashboards with filters and slicers.

## 📊 Power BI Dashboards

### 1. Sales Dashboard

Analyzes overall sales performance through:

* Total Revenue
* Total Orders
* Average Order Value (AOV)
* Revenue Trends
* Year-wise Revenue
* Revenue by Category
* Top-Performing Categories

### 2. Product Dashboard

Provides insights into product and category performance:

* Total Products
* Total Categories
* Average Product Price
* Quantity Sold
* Orders by Category
* Top Categories
* Category Contribution

### 3. Delivery Dashboard

Evaluates delivery efficiency and order fulfillment:

* Average Delivery Days
* Delivery Status
* Early Deliveries
* On-Time Deliveries
* Late Deliveries
* Not Delivered Orders
* State-wise Average Delivery Time

### 4. Seller Dashboard

Analyzes seller performance and contribution:

* Total Sellers
* Seller Revenue
* Total Orders
* Average Revenue per Seller
* Top 10 Sellers
* Seller Revenue by State

### 5. Payment & Review Analysis

Examines payment patterns and customer satisfaction:

* Payment Type
* Payment Revenue
* Transaction and Order Distribution
* Average Review Score
* Category-wise Review Score
* Reviewed Customers
* Non-Reviewed Customers

## 📈 Project Outcomes

* Cleaned and prepared raw e-commerce datasets using Python.
* Created useful analytical columns for business reporting.
* Built a structured relational database in MySQL.
* Established relationships using primary and foreign keys.
* Performed business analysis using SQL.
* Developed DAX measures and KPIs in Power BI.
* Created five interactive dashboards covering different business areas.
* Converted complex transactional data into understandable business insights.

## ⚠️ Challenges Faced

* Handling missing and duplicate data
* Managing different data types
* Creating relationships between multiple tables
* Handling missing product categories
* Developing delivery-status logic
* Performing multi-table SQL analysis
* Building correct Power BI relationships and DAX measures

## 🚀 Future Scope

* Sales forecasting to predict future revenue
* Customer segmentation based on purchasing behavior
* Seller performance scoring using revenue, orders, delivery, and reviews
* Late-delivery prediction using machine learning
* Product recommendations based on customer purchase behavior
* Automated Power BI dashboard refresh
* Advanced geographic analysis

## 📂 Repository Structure

The repository can be organized as follows. Adjust the folder names to match your uploaded files.

```text
Olist-Ecommerce-Data-Analytics/
│
├── Python/
│   └── Data Cleaning and Preparation
│
├── SQL/
│   └── SQL Business Analysis Queries
│
├── PowerBI/
│   └── Power BI Dashboard
│
├── Reports/
│   └── Project Report
│
└── README.md
```

## 📝 Conclusion

This project demonstrates an end-to-end data analytics workflow, from cleaning and transforming raw data using Python to database modeling with MySQL, business analysis with SQL, and interactive reporting with Power BI and DAX.

It showcases practical skills in data preparation, relational database design, SQL querying, KPI development, data visualization, and business analysis while demonstrating how raw e-commerce data can be transformed into meaningful business insights.

## 👨‍💻 Skills Demonstrated

`Python` `Pandas` `MySQL` `SQL` `Data Cleaning` `Data Modeling` `DAX` `Power BI` `Data Visualization` `Business Analysis`
