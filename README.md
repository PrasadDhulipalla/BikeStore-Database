# BikeStore-Database
Project2
Bike Store Data Analytics Project
A data analysis and reporting project built on a Bike Store sales dataset from Kaggle. The data was cleaned, normalized, and structured into a relational PostgreSQL database using Star and Snowflake schemas. Performed SQL-based analytics and visualized key business KPIs using Power BI.

📌 Project Goals
Design a normalized database for bike store operations.

Implement data models using Star and Snowflake schemas.

Perform SQL queries to analyze sales, customer behavior, and product performance.

Create dashboards to visualize insights for decision-making.

🗂️ Dataset Overview
Bike Sales Data (from Kaggle)

Key tables: customers, orders, products, categories, employees, stores

🛠️ Tools Used
Database: PostgreSQL (pgAdmin)

Languages: SQL

Schema Design: Star and Snowflake models

Visualization: Power BI (or Excel optional)

📊 Key Insights Extracted
Best-selling bike categories and brands

Monthly sales performance

Revenue by store and employee

Order volume and product return trends

Top customers by purchase value

📁 Project Structure
pgsql
Copy
Edit
bike-store-database/
├── data/                     # Raw CSV or sample data
├── sql/                      # Database schema & SQL queries
├── visuals/                  # Dashboards and ERD screenshots
├── README.md
└── bike_store.sql            # Full database dump file
⚙️ How to Use
Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/bike-store-database.git
Import bike_store.sql into your PostgreSQL server.

Open and run the SQL scripts in /sql/.

Explore visualizations using Power BI or any BI tool.

✅ Features Demonstrated
Normalized relational schema (3NF)

Star and Snowflake data modeling

SQL-based analytics: aggregation, joins, grouping
