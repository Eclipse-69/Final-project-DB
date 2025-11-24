# Final-project-DB
📊 Coffee Shop Database & AI SQL Agent
Final Project – Databases Course
📌 Overview

This project is a complete end-to-end implementation of a Relational Database System for a coffee shop, combined with an AI-powered Text-to-SQL agent (LangChain + Gemini).
It includes:

Normalized MySQL relational database

Dataset with >1000 rows in every table

Indexing and optimization

Python-based AI agent generating SQL queries

Analytical VIEWs

ER Diagram & full documentation

The project demonstrates database engineering, analysis, SQL development, and AI integration.


🧱 Database Schema
Tables:

customers — customer dataset

products — coffee shop menu

orders — order header

order_items — items inside orders

deliveries — shipped/delivered info

reviews — customer feedback logging

Key Relations:

customers 1—∞ orders

orders 1—∞ order_items

products 1—∞ order_items

orders 1—1 deliveries

orders 1—∞ reviews


📈 SQL Insights (VIEWs)
Project includes at least 3 analytical VIEWs, such as:

✅ VIEW 1: Top Customers by Spending (Клиенты больше всего)               (top_customers)
✅ VIEW 2: Product Sales Summary  (Количество продаж + общая выручка)     (product_sales_summary )
✅ VIEW 3: Delivery Performance (Средняя задержка доставки по заказам)    (delivery_performance)
✅ VIEW 4: Average Product Rating  (Средний рейтинг каждого продукта)     (product_ratings)

