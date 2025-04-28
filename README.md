# Grocery-Store-Database-Degisn
Project Overview
This project is a full-stack relational database system designed for a grocery store transitioning into online shopping with delivery options.
Our platform supports customer account creation, inventory management, order processing, delivery tracking, and business analytics.
It’s built to handle real-world business needs, scale efficiently, and optimize the shopping experience based on customer behavior.

**Features**
Customer Accounts: Manage profiles, addresses, orders, and wishlists.

Inventory Management: Live updates on stock levels, low-stock alerts.

Order Processing: Track orders from checkout to delivery.

Employee Management: Assign deliveries, monitor working hours.

Supplier Management: Track item sourcing and delivery dates.

Rewards System: Earn and redeem points for purchases.

Reviews: Customers can leave feedback and rate products.

Business Intelligence: Data queries for sales tracking, top products, inventory shortages, and customer behavior.

**Tech Stacks**
Database: MySQL

Modeling: Lucidchart for ERD and relational models

Scripts: DDL + DML for schema creation and data insertion

Business Insights: Advanced SQL queries for operational reports

**Key Business Questions Answered**
What’s today’s total sales revenue?

What are the top 5 best-selling products and their suppliers?

Which products are running low on stock?

What are customers saying about our products?

How do employee hours and locations correlate with delivery efficiency?

**Database Design Overview**
21 Core Entities including Customer, Order, Item, Inventory, Employee, Supplier, Review, Rewards, Wishlist.

Relationship Modeling: One-to-One, One-to-Many, and Many-to-Many structures.

Constraints: Foreign keys, unique keys, check constraints for data integrity.

Major Highlights:

Every customer must have a unique email.

Products must have at least one category and a nonzero price.

Suppliers are tied directly to items they provide.

Full support for reward points and discounts.

Real-time delivery and inventory updates.

**Installation**
To spin this up locally:

Clone this repo.

Load the .sql scripts into your MySQL server.

Populate with sample data (40+ rows per major transactional table).

Run the business queries to validate the setup.

**Team**
Developed by:

Cygen Stanley

Junruiyi Xie

Bao Nguyen

Ahmad Alhaimi

**Future Enhancements**
Build a full-stack web app frontend for customer interactions.

Integrate real-time delivery tracking via APIs.

Implement machine learning for predictive inventory management.

Add multi-payment gateway support (Venmo, PayPal, crypto).

**License**
This project is intended for educational and portfolio use.
If you plan to expand or deploy commercially, please credit the original authors.
No license granted for direct resale without major modification.

