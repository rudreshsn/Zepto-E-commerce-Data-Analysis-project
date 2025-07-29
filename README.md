# Zepto-E-commerce-Data-Analysis-project
This project demonstrates data exploration, cleaning, and analysis on a simulated grocery dataset inspired by Zepto. The SQL scripts are written to help derive meaningful insights for business decisions such as inventory management, product pricing strategy, and category performance.

## Dataset
The dataset (zepto_v2.csv) contains product details including:
SKU ID
Product Category & Name
MRP & Discounted Selling Price
Available Quantity
Product Weight (in grams)
Out of Stock status

## Key SQL Operations
### Data Exploration
Total row count, sample data preview
Null value detection
Unique product categories
Stock vs out-of-stock analysis
Repeated product names

### Data Cleaning
Removal of products with zero MRP or selling price
Conversion of price values from paise to rupees

### Data Analysis
Top 10 products with the highest discounts
High-MRP products currently out of stock
Estimated revenue by category
High MRP products with low discounts
Top 5 categories by average discount
Price-per-gram value for better product pricing
Categorization of products based on weight (Low, Medium, Bulk)
Total inventory weight per category

### Tools Used
PostgreSQL
SQL (DML, DDL, Aggregates, CASE statements, etc.)
