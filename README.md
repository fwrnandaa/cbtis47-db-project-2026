# CBTis 47 - Database Project 2026

## ☕ Sistema de Gestión para un Restaurante

## 👥 Team Members
- Alexis Benitez Fuentes
- Gabriel Eduardo Córdoba Perez
- Fernanda Martínez Martínez 
- Karen Yazbeth Rivera Aguirre

---

## 📌 Project Description

This project consists of the design and development of a relational database for a coffee shop management system.

The main purpose is to organize and manage information related to customers, products, employees, orders, and payments.  
The database will help control sales, inventory, and customer records efficiently.

---

## 🎯 General Objective

Design a relational database that complies with the Third Normal Form (3NF), ensuring proper data storage and integrity for the coffee shop.

---

## 📋 Specific Objectives

- Register products offered by the coffee shop.
- Manage customer orders.
- Store employee information and roles.
- Handle payments and payment methods.
- Generate sales reports and analytical queries.

---

## 💡 Justification

Many small coffee shops manage information manually or in an unorganized way.

This database system will:

- Control daily sales.
- Identify best-selling products.
- Manage inventory.
- Organize customer information.
- Reduce record errors.

---

## 🗂 Main Entities

The database includes the following tables:

- Customer
- Product
- Category
- Order
- Order_Detail
- Employee
- Payment

---

## 🔗 System Relationships

- One customer can place many orders (1:N).
- One order can include multiple products (N:M).
- One product belongs to one category (1:N).
- One employee attends many orders (1:N).
- One order generates one payment (1:1).

---

## 📦 Project Scope

The project includes:

- Entity-Relationship Diagram (ERD)
- Table creation with primary and foreign keys
- Mock data insertion
- Complex queries using JOIN, SUM, and COUNT
- User creation and permission management
- Test cases and validation scripts

---

## 🛠 Technologies Used

- MySQL
- SQL
- GitHub
- Mermaid (for ER diagram)
