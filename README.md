# Order-Management-System
Order Management System using SQL with JOINs and Subqueries to manage customers, products, and order history.

# 🛒 Order Management System (SQL-Based Project)

A relational database project built using SQL that manages customers, products, and orders.  
This system demonstrates the use of **JOINs, Subqueries, Aggregate Functions, and Relational Database Concepts** to efficiently handle order processing and customer purchase history.

---

## 📌 Project Overview

The Order Management System is designed to:

- Store customer information
- Manage product inventory
- Record customer orders
- Track ordered items
- Display detailed customer order history
- Perform business analysis using SQL queries

This project focuses on writing optimized SQL queries using multi-table relationships.

---

## 🗂 Database Schema

The system consists of the following tables:

1. Customers  
2. Products  
3. Orders  
4. Order_Items  

### 🔹 Entity Relationships

- One Customer → Many Orders  
- One Order → Many Order Items  
- One Product → Many Order Items  

---

## 🛠 Technologies Used

- SQL (MySQL / PostgreSQL Compatible)
- Relational Database Concepts

---

## 🚀 Key Features

✔ Multi-table relational database design  
✔ INNER JOIN operations  
✔ GROUP BY and HAVING clauses  
✔ Subqueries for advanced filtering  
✔ Customer order history display  
✔ Order total calculation  
✔ High-value customer analysis  

---

## 📊 Sample Functionalities

### 🔹 View All Orders with Customer Details  
Uses JOIN to combine Customers and Orders.

### 🔹 Calculate Total Amount per Order  
Uses SUM() with GROUP BY.

### 🔹 Customers with Multiple Orders  
Uses subqueries with HAVING clause.

### 🔹 Complete Customer Order History  
Displays:
- Customer Name  
- Order ID  
- Product Name  
- Quantity  
- Total Price  

---

## 📂 Project Structure

Order-Management-System/
│
├── schema.sql
├── sample_data.sql
├── queries.sql
└── README.md


---

## 🎯 Learning Outcomes

- Designing normalized relational databases  
- Writing optimized SQL queries  
- Understanding multi-table relationships  
- Applying business logic using SQL  

---

## 🔮 Future Enhancements

- Add Payment table  
- Implement Stock auto-update trigger  
- Stored Procedures for order processing  
- Integrate with Java / Spring Boot  
- Add reporting dashboard  

---

## 👨‍💻 Author

**Hemachandra Talluri**  
Aspiring Full Stack Developer | SQL & Java Enthusiast  

