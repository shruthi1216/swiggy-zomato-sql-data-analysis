🍔 Swiggy / Zomato Data Analytics Case Study

📌 Project Overview

This project is a beginner-level **Food Delivery Data Analytics Case Study** developed using **Oracle SQL**.

The project simulates a food delivery platform like Swiggy or Zomato and analyzes customers, restaurants, orders, food items, revenue, cancellations, and customer spending.

The main objective is to use SQL to answer real-world business questions and generate useful insights from transactional data.

---

🎯 Project Objective

The project focuses on:

* Analyzing restaurant revenue
* Understanding customer spending behavior
* Tracking monthly orders and revenue
* Identifying top-performing restaurants
* Analyzing food item sales
* Comparing cuisine performance
* Calculating restaurant cancellation rates
* Analyzing customer order recency
* Applying advanced SQL techniques for business analysis

---

🛠️ Tools & Technologies

* **Database:** Oracle SQL
* **Language:** SQL
* **Tool:** Oracle SQL Developer
* **Version Control:** GitHub

---

🗄️ Database Tables

The project contains 4 main tables:

| Table           | Description                              |
| --------------- | ---------------------------------------- |
| `users`         | Stores customer information              |
| `restaurants`   | Stores restaurant details                |
| `orders`        | Stores customer order transactions       |
| `order_details` | Stores food items included in each order |

### Relationships

* `users` → `orders`
* `restaurants` → `orders`
* `orders` → `order_details`

Primary keys and foreign keys were used to maintain relationships between the tables.

---

📊 Business Analysis Performed

The project contains **11 business-driven SQL queries**:

1. Restaurant-wise Revenue Analysis
2. Users Who Have Never Placed an Order
3. Monthly Orders and Revenue
4. Customer Spending Analysis
5. Top 3 Restaurants by City
6. Month-over-Month Revenue Growth
7. Customer Cumulative Spending
8. Best-Selling Item per Restaurant
9. Cuisine-wise Performance
10. Restaurant Cancellation Rate
11. Customer Recency Analysis

---

🧠 SQL Concepts Used

The project demonstrates the following SQL concepts:

* `CREATE TABLE`
* `INSERT`
* `COMMIT`
* Primary Keys
* Foreign Keys
* `NOT NULL`
* `UNIQUE`
* `CHECK`
* `DEFAULT`
* `JOIN`
* `LEFT JOIN`
* `GROUP BY`
* `HAVING`
* `ORDER BY`
* `CASE`
* `NVL`
* `TO_CHAR`
* `TRUNC`
* `ROUND`
* `NULLIF`
* Common Table Expressions (CTE)
* `DENSE_RANK()`
* `LAG()`
* Window Functions
* Aggregate Functions

---

📈 Key Insights

The analysis helps identify:

* Restaurants generating higher revenue
* Customers with higher spending
* Monthly revenue trends
* Top restaurants within cities
* Best-selling food items
* High-performing cuisines
* Restaurant cancellation rates
* Customers based on their most recent order

These insights can support business decisions related to **restaurant performance, customer engagement, revenue growth, and operational improvement**.

---

📁 Project Structure

```text
swiggy-zomato-sql-data-analysis/
│
├── README.md
│
└── swiggy_zomato_analysis.sql
```

---

▶️ How to Run the Project

1. Download or clone this repository.
2. Open `swiggy_zomato_analysis.sql` in **Oracle SQL Developer**.
3. Run the table creation statements.
4. Run the INSERT statements to add the sample data.
5. Execute the analytical queries individually to view the results.

---

📌 Conclusion

This project demonstrates how **Oracle SQL can be used to transform transactional food delivery data into meaningful business insights**.

It helped strengthen practical skills in **database design, SQL querying, joins, aggregations, CTEs, window functions, and business-oriented data analysis**.

---

👩‍💻 Author

**Shruthi M.**

Aspiring Data Analyst | SQL | Power BI | Excel | Python
