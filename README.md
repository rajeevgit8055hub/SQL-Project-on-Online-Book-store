# 📘 My First SQL Project: Online Bookstore Data Analysis
A complete SQL-based data analysis project on a fictional online bookstore using PostgreSQL. This project demonstrates how to clean, query, and analyze real-world datasets to extract business insights such as sales trends, revenue, inventory, and customer behavior using 20+ well-structured SQL queries.

---

## 📌 Project Overview

This project centers around a fictional **Online Bookstore**, where I analyzed transactional and inventory data using **PostgreSQL**.  
By performing SQL operations on this dataset, I uncovered actionable business insights that simulate real decision-making processes in **e-commerce or retail environments**.

The goal was not only to query data but also to answer business questions, understand customer behavior, and monitor performance indicators (KPIs) like revenue, stock, and high-performing books/authors.

---

## 📂 Datasets Used

The analysis was based on three CSV files, imported into PostgreSQL as relational tables:

- `books.csv` – Contains book information (title, author, genre, price, stock)  
- `customers.csv` – Contains customer data (name, city, country)  
- `orders.csv` – Contains order transactions (book ID, customer ID, quantity, total amount, order date)

---

## 🎯 Project Objectives

The primary goals of this project were to:

📚 Analyze book sales performance  
🧍 Understand customer purchasing behavior  
💰 Calculate total revenue  
📦 Monitor inventory levels  
📝 Identify top authors and regions contributing to profit

---

## ⭕ Business Problems Addressed

The bookstore aimed to answer the following real-world business questions:

- Which genres and books are performing the best?  
- Who are the most loyal and profitable customers?  
- What is the total revenue generated from sales?  
- How much stock remains after fulfilling all orders?  
- Which cities and regions generate the most value?

---

## 🛠️ Methodology

I approached this project in a structured, multi-step manner:

### 📥 Data Import  
All CSV files were cleaned and imported into PostgreSQL tables: `books`, `customers`, and `orders`.

### 🔎 Basic SQL Queries  
Used `SELECT`, `WHERE`, `ORDER BY` to perform filtering, sorting, and basic exploration.

### ⚙️ Advanced SQL Analysis  
Applied:

- `JOIN` operations for combining relational tables  
- `GROUP BY` and `HAVING` for aggregated insights  
- `SUM`, `AVG`, `COUNT` for revenue, quantity, and customer metrics

### 📊 Business KPI Modeling  
Designed queries to track key metrics like:

- Total revenue: `SUM(total_amount)`  
- Inventory status: `stock - SUM(quantity)`  
- Top-performing authors and books  
- High-value customers and profitable regions

---

## 🔍 Key Insights & Solutions

Here are some actionable insights derived from the SQL analysis:

✅ **Top-Selling Genre:** Fiction emerged as the highest-selling category  
✅ **Customer Segmentation:** Identified high-spending customers and cities where order totals exceeded ₹30  
✅ **Revenue Tracking:** Calculated total income using aggregated queries on order amounts  
✅ **Inventory Check:** Determined remaining stock using `LEFT JOIN` and `SUM(quantity)` calculations  
✅ **Top Contributors:** Listed authors and books with the highest number of sales

---

## 📈 Sample SQL Queries Used

### 🟢 Basic Queries:

- List all customers from Canada  
- Show books published after 1950  
- Retrieve books in the Fiction genre  
- Orders placed in November 2023  

### 🔵 Advanced Queries:

- Total books sold per genre  
- Average book price in the Fantasy genre  
- Customers who placed 2 or more orders  
- Most frequently ordered book  
- Top spending customer by total amount  
- Remaining stock per book after all orders  

💡 *20+ SQL queries were written and executed to simulate business analysis tasks.*

---

## 🧠 Skills Gained

Through this project, I gained hands-on experience in:

- Writing real-world SQL queries to answer business questions  
- Translating KPIs into database logic  
- Joining and managing multiple relational tables  
- Building a business-focused, data-driven problem-solving mindset

---

## 🔑 Why This Project Matters

📌 My first complete SQL project  
📁 A strong portfolio project for GitHub and LinkedIn  
🧠 Helped me bridge the gap between theory and practice  
💬 Prepared me for interviews, internships, and freelance work  
🚀 Built confidence for future projects involving dashboard creation, reporting, and data analytics

---

## ✅ Conclusion

This project transformed me from a SQL learner into someone capable of solving real-world business challenges using data.  
By analyzing structured datasets with PostgreSQL and writing over 20 queries, I not only improved my SQL proficiency but also developed the mindset of a business-oriented data analyst.

From CSV files to insights, from raw data to real KPIs — this project represents a **key milestone** in my data analytics journey.

---

![Bookstore](Bookstore.jpeg)
