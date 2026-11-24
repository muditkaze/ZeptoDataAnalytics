# Zepto Inventory Data Analysis Using SQL

## Project Overview

This project focuses on analyzing Zepto's product and inventory dataset using SQL. The objective is to explore product pricing, discounts, stock availability, and inventory distribution to understand business performance and identify opportunities for better inventory management.

The project covers data exploration, data cleaning, and business-oriented data analysis using PostgreSQL.

## Tools & Technologies

- PostgreSQL
- SQL
- GitHub

## Dataset Description

The dataset contains product-level information across different categories.

| Column                 | Description                   |
| ---------------------- | ----------------------------- |
| sku_id                 | Unique product SKU identifier |
| category               | Product category              |
| name                   | Product name                  |
| mrp                    | Maximum retail price          |
| discountPercent        | Discount percentage           |
| availableQuantity      | Available stock quantity      |
| discountedSellingPrice | Selling price after discount  |
| weightInGms            | Product weight in grams       |
| outOfStock             | Stock availability status     |
| quantity               | Product quantity field        |

## Project Workflow

### 1. Data Exploration

- Examined the total number of records.
- Previewed sample data to understand the dataset.
- Checked for missing values.
- Identified unique product categories.
- Compared in-stock and out-of-stock products.
- Identified product names associated with multiple SKUs.

### 2. Data Cleaning

- Identified products with zero prices.
- Removed records with zero MRP.
- Converted product prices from paise to Indian rupees.

### 3. Data Analysis

The following business questions were explored using SQL:

1. What are the top 10 products offering the highest discount percentage?
2. Which high-priced products are currently out of stock?
3. What is the estimated inventory sales value for each product category?
4. Which products have an MRP above ₹500 and a discount below 10%?
5. Which five product categories offer the highest average discount?
6. Which products offer the best value based on price per gram?
7. How can products be classified into Low, Medium, and Bulk weight categories?
8. What is the total inventory weight for each product category?

## SQL Concepts Used

- CREATE, DROP, UPDATE and DELETE
- SELECT and DISTINCT
- WHERE and logical operators
- GROUP BY and HAVING
- ORDER BY and LIMIT
- Aggregate functions (COUNT, SUM, AVG)
- CASE statements
- Data filtering and transformation
- Arithmetic calculations

## Business Applications

This analysis can help businesses:

- Identify high-value products that require restocking.
- Understand discount strategies across product categories.
- Compare products based on pricing and weight.
- Estimate potential sales value from available inventory.
- Improve inventory planning and stock management.
- Identify opportunities for better pricing decisions.

## How to Run This Project

1. Install PostgreSQL.
2. Create a new database.
3. Execute the table creation query.
4. Import the dataset into the `zepto` table.
5. Execute the data exploration and cleaning queries.
6. Run the analytical queries to explore the business questions.

## Limitations

The estimated inventory sales value represents the potential value of available stock, not actual revenue generated from completed sales.

The analysis is based on the provided dataset and does not represent Zepto's real-time inventory.

## Conclusion

This project demonstrates the practical application of SQL in solving retail and e-commerce business problems. It helped me develop my understanding of data cleaning, exploratory data analysis, inventory analysis, and business-oriented SQL queries.

## Acknowledgements

This is a learning and portfolio project based on an existing Zepto SQL data analysis project.&#x20;
