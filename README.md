# Online Shopping Website Database

This is a database for an online shopping website that allows users to browse and purchase products. The database stores information about the products, orders, and customers.

# Getting Started
To set up the database, you will need to run the SQL script provided in this project. The script creates the necessary tables and adds sample data.

To access the database, you will need a database management system such as MySQL, SQL Server, or PostgreSQL. You can use your preferred SQL client or command-line interface to connect to the database and run SQL queries.

# Database Schema
The database schema consists of four tables:

- Products: stores information about the products, including the product name, price, and description.
- Customers: stores information about the customers, including the customer name, email address, and shipping address.
- Orders: stores information about the orders, including the order date, customer ID, and total cost.
- OrderDetails: stores information about the order details, including the order ID, product ID, quantity, and price.

The tables are related as follows:

A product can be included in multiple order details, but a single order detail can only include one product. This is a one-to-many relationship between Products and OrderDetails.
A customer can place multiple orders, but each order can only be placed by one customer. This is a one-to-many relationship between Customers and Orders.
An order can include multiple order details, but each order detail can only belong to one order. This is a one-to-many relationship between Orders and OrderDetails.