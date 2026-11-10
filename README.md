# DBMS_Capstone_Project-SEM3-

INTRODUCTION:
An Online Marketplace System is a digital platform that allows multiple sellers to showcase and sell their products to customers through the internet. It provides a convenient environment where customers can explore different products, compare prices, place orders, and share their feedback, while sellers can manage their product listings and track sales.
With the rapid growth of e-commerce, managing large amounts of information related to customers, sellers, products, orders, and transactions has become increasingly important. A Database Management System (DBMS) helps organize this information systematically, making data storage, retrieval, and management more efficient and reliable.
The main purpose of this project is to design and implement a relational database for an Online Marketplace System using MySQL. The database consists of seven major tables: Sellers, Customers, Categories, Products, Orders, Order_Items, and Reviews. These tables are connected through primary keys and foreign keys to maintain relationships and ensure data consistency.
The project uses various SQL operations such as CREATE, INSERT, SELECT, UPDATE, DELETE, JOIN, and aggregate functions to manage and retrieve information. It also incorporates advanced DBMS concepts such as composite indexing, FULLTEXT indexing, views, stored procedures, and window functions to improve query performance and support data analysis.
Furthermore, the system helps analyze total sales, identify top-selling products, evaluate seller performance, calculate customer lifetime value, and understand customer purchasing patterns.
Overall, the Online Marketplace System demonstrates how database management concepts can be applied to a real-world e-commerce application. It provides practical knowledge of relational database design, SQL query execution, data analysis, and database optimization.

ER DIAGRAM:
<img width="2600" height="1800" alt="Online_Marketplace_ER_Diagram_Dark" src="https://github.com/user-attachments/assets/0d2bd171-7729-4696-83fe-fdbcadaf50ab" />

Problems Being Faced :
1.	Difficulty in Managing Data: Managing customer, seller, product, and order details separately can lead to confusion and duplication of records.
2.	Data Redundancy: Repeated storage of the same information increases database size and may cause inconsistencies.
3.	Difficulty in Tracking Orders: Tracking customer orders, order dates, product quantities, and order details becomes complicated without proper database management.
4.	Lack of Sales Analysis: Identifying sales trends and top-selling products is difficult without suitable SQL queries and data analysis.
5.	Difficulty in Evaluating Sellers: Comparing seller performance based on total sales, customer ratings, and returns can be challenging.
6.	Customer Satisfaction Analysis: Collecting and analysing customer reviews and ratings is necessary but can be difficult when review data is not properly organized.
7.	Slow Data Retrieval: Searching and retrieving product or order information from large datasets can take more time without proper indexing.
8.	Limited Business Insights: Without advanced database queries, it is difficult to identify customer purchasing patterns, spending categories, and monthly sales growth.

Proposed Solution:
The proposed solution is to develop an Online Marketplace Database Management System using MySQL. The system will organize and manage marketplace information through a structured relational database.
•	Centralized Database: Create a single database to store customer, seller, product, category, order, and review information.
•	Structured Database Design: Use properly related tables with primary keys and foreign keys to maintain data consistency and reduce redundancy.
•	Efficient Order Management: Store and manage order details, including customers, products, quantities, prices, and order dates.
•	Sales Analysis: Use SQL queries to identify sales trends, monthly revenue, and top-selling products.
•	Seller Performance Evaluation: Create views to analyse seller performance using available sales and rating information.
•	Customer Satisfaction Analysis: Use customer reviews and ratings to understand product satisfaction.
•	Improved Query Performance: Implement composite indexes and FULLTEXT indexes to improve data retrieval where appropriate.
•	Advanced Data Analysis: Apply SQL window functions such as RANK(), LAG(), MIN(), and NTILE() to analyse product rankings, monthly growth, customer cohorts, and spending patterns.




