# Task-4-SQL-for-Data-Analysis
Analyzed the Bike Store relational database using SQL. Created normalized tables from CSVs, ran complex queries using JOINs, subqueries, aggregates, views, and indexes to extract insights. Included SQL scripts, outputs, and screenshots.
#  Objective
Analyze and extract insights from the **Bike Store Relational Database** using SQL. This task involves creating normalized tables, importing data from CSV files, and running various SQL queries to perform data analysis.
# Tools Used
 **MySQL** (Workbench)
 **Kaggle Dataset**: [Bike Store Relational Database]
 **Dataset Link** : https://storage.googleapis.com/kaggle-data-sets/3649090/6340459/bundle/archive.zip?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=gcp-kaggle-com%40kaggle-161607.iam.gserviceaccount.com%2F20250606%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20250606T144453Z&X-Goog-Expires=259200&X-Goog-SignedHeaders=host&X-Goog-Signature=32d78c0f65c7d72e5b5beee11de204a0a40c5a724d2a25281129e8ad910705b81dd23384f080b4b8485f46b7ba130b9a5fd72e32e582e68ab0a9d65fa7887fefca582a16bfd1b28c0fc0bb9f439e3a13d2536b677946943d2835c5380d5b87063072705709d5b8e18cb2db90c090fc2d9ec2506d8dd0e76bb909ab38f4fbe340355ef4dedf2a9f81431bae8947839af594689e182deda8c8329fa49fa0b7c2624b1b748721cb5801d7a1712739557e58dd01182c4aae8ed94c0870526cf72b872fb4a07084398ef48d62fcfa38261de73c8c1198ea345e97b65ec0de0435e35a13004c046445b31d54beb8c18148e349fdde74563def712f9e66d26b9d03e8f4
 **CSV Files**: Used to create and populate tables.
 **GitHub**: For version control and project submission.
 # Database Design

Normalized database with the following tables:

 `brands`
 `categories`
 `products`
 `customers`
 `orders`
 `order_items`
 `staffs`
 `stores`
 `stocks`

Each table was created using SQL `CREATE TABLE` statements, with appropriate `PRIMARY KEYS`, `FOREIGN KEYS`, and `INDEXES` for performance.

# What I Did

 Designed and created **individual relational tables** to avoid redundancy.
 Loaded data into MySQL using `LOAD DATA INFILE`.
 Performed analysis using:
   `SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`
   `JOINs`
   **Subqueries**
   **Aggregate Functions**: `SUM`, `AVG`, `COUNT`
   **Views** for summary reports

# Sample Queries Included

- List all customers from California
- Total customers by state
- Revenue by product
- Orders handled by each staff
- Products with quantity in stock per store
- Top 5 selling products
- Monthly order count
- Total revenue by brand
- Average discount per product
- Customers who placed more than 2 orders
- Create a view for sales summary

# Screenshots
Screenshots of SQL output have been included in the `screenshots.


