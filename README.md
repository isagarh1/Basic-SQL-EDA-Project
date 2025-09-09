# 📊 SQL Exploratory Data Analysis (EDA) Project

📌 **Overview**:

- This project demonstrates Exploratory Data Analysis (EDA) using PostgreSQL.
   
- The dataset is structured into a star schema with dimension and fact tables (customers, products, and sales).

- The goal of the project is to:

#### Explore the database schema:

- Perform descriptive statistics and aggregations.

- Answer key business questions using SQL.

- Generate insights about customers, products, and sales performance.

🗂 **Project Structure** :

- Database Setup

- Created a database Analytics_db.

- Created schema gold.

- Built 3 core tables:

- dim_customers

- dim_products

- fact_sales

**Exploration & Profiling** :

- Checked available schemas and tables using INFORMATION_SCHEMA.

- Explored columns, datatypes, and distinct values.

- Verified date ranges and customer demographics.

**Descriptive Analysis** :

- Calculated first and last order dates.

- Found youngest and oldest customers.

- Computed overall sales, average price, total quantity, total orders, products, and customers.

- Combined business KPIs into a single report using UNION ALL.

**Dimensional Analysis**

- Customers by country and gender.

- Products by category.

- Average product cost by category.

- Total revenue contribution by each category.

- Revenue contribution by each customer.

- Quantity distribution across countries.

**Ranking Analysis**

- Top 5 products by revenue.

- Bottom 5 products by revenue.

📈 **Key Insights**

- Sales Timeline :
  
  First order date: "2010-12-29"
    
  Last order date: "2014-01-28"

- Customer Demographics :
  
  Total Customers: 18484
  
  Youngest Customer Age: 39 years

  Oldest Customer Age: 109 years

  Customers are spread across multiple countries with highest concentration in [United STates].

- Gender Distribution :
  
  Male: 9341 customers
  
  Female: 9128 customers    

- Business Metrics :

  Total Sales: 29356250

  Total Quantity Sold: 60423 units

  Average Price: 486.04

  Total Orders: 27659

  Total Products: 295

  Total Customers: 18484

- Category Analysis :

  ["Bikes"] generated the highest revenue.

  ["Clothing"] underperformed in terms of sales.


⚙️ **Tech Stack**

- SQL (PostgreSQL / PgAdmin4)

- Star Schema (Dimensional Modeling)

📜 License :

This project is released under the MIT License – free to use and modify.

✨ **With this project, I showcased my ability to**:

- Perform SQL-based data exploration.

- Derive business insights from relational data.

- Use aggregation, joins, ranking, grouping, and date functions effectively.
