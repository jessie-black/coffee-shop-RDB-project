# coffee-shop-RDB-project
### Final Project in IBM course **Introduction to Relational Databases** 
Part of *IBM's Data Engineering Professional Certificate*

## Software Used
PostgreSQL Database
IBM Db2 Database
MySQL
pgAdmin

## Data used
Coffee shop sample data retrieved <a href = https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/12/beanie-coffee-1113>here</a>

## Tasks
- Identify entities & attributes
- Create ERD diagram using pgAdmin ERD Tool
- Normalize tables
- Define keys and relationships
- Create databases objects by generating and running the SQL script from the ERD Tool
- Create a view and export the data
- Create a materialized view and export the data
- Import data into a Db2 database
- Import data into a MySQL database

## Skills learned/practiced
- Creating ERD diagrams
- Normalizing tables to 1st normal form 
- Generating SQL from ERD diagrams in pgAdmin
- Using pgAdmin, DB2 database, and MySQL database for creating and viewing tables with SQL

## Most challenging aspect
- Normalization of the sales_transactions table was a minor hurdle, as I knew that product_id, quanity, and price needed to be removed to a separate table, but wasn't sure what the other table should be named or how it should be identified to avoid repeating the same issue. sales_detail was the provided answer later in the project, so I went with that instead of my initial idea of transaction_item. Normalizing the product table was no problem at all, as the external table (product_type) was immediately obvious from the data.
