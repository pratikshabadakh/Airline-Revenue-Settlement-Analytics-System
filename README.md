# ✈️ Airline-Revenue-Settlement-Analytics-System

## Project Overview

The Airline Revenue & Settlement Analytics System is a SQL-based data analytics project designed to simulate airline financial operations including bookings, payments, cancellations, and refunds.
The system performs revenue analysis, route performance evaluation, and financial impact assessment using structured SQL queries.
This project is aligned with real-world airline technology platforms used for revenue accounting and settlement processing.


##  Problem Statement

Airlines manage large volumes of transactional data related to bookings, payments, and refunds.
Analyzing this data efficiently is essential for:

* Monitoring revenue trends
* Evaluating route performance
* Identifying cancellation patterns
* Understanding refund impact
* Supporting financial decision-making

The challenge is to design a structured database system and extract meaningful insights using SQL.

##  Objective

 Design a normalized relational database for airline operations
 Store booking and financial transaction data
 Perform revenue and settlement analysis using SQL Implement advanced SQL concepts (CTE, Window Functions)
 Generate business insights from transactional data
 Create dashboard-ready analytics outputs


##  Tech Stack

Database: Oracle SQL
Query Language: SQL
Visualization (Optional): Power BI
Version Control: Git & GitHub

##  Database Schema

The system includes the following tables:

* Airlines
* Routes
* Flights
* Passengers
* Bookings
* Payments
* Refunds

### Relationships

* One Airline → Many Flights
* One Route → Many Flights
* One Passenger → Many Bookings
* One Booking → One Payment
* One Booking → Optional Refund


##  Key Features

✔ Revenue per airline analysis
✔ Monthly revenue trend tracking
✔ Route-wise performance analysis
✔ Cancellation rate calculation
✔ Refund impact assessment
✔ Ranking of top-performing routes
✔ Financial settlement simulation


## SQL Concepts Used

* INNER JOIN / LEFT JOIN
* GROUP BY & HAVING
* Aggregate Functions (SUM, COUNT)
* Subqueries
* CTE (Common Table Expressions)
* Window Functions (RANK, ROW_NUMBER)
* Date Functions
* Foreign Key Constraints

##  Sample Business Queries

1. Total revenue per airline
2. Monthly revenue trend analysis
3. Top 5 revenue-generating routes
4. Cancellation rate per route
5. Net revenue after refunds


##  Business Insights Generated

* Identified highest revenue routes
* Measured cancellation percentages
* Evaluated refund impact on net revenue
* Tracked month-wise financial growth
* Analyzed payment method distribution


##  How to Run the Project

1. Create database tables using provided DDL scripts
2. Insert sample data using data generation scripts
3. Execute SQL queries for analytics
4. (Optional) Connect to Power BI for visualization


##  Future Enhancements

* Add dynamic pricing simulation
* Implement stored procedures for automated reporting
* Add indexing for performance optimization
* Expand dataset for large-scale simulation
* Deploy as a web-based analytics dashboard




