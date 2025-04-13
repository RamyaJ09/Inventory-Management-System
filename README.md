# Inventory-Management-System
 # 📦 Inventory Management System

A user-friendly desktop application developed using **Java Swing (JFrame)** and **MySQL**, designed to streamline and automate the process of managing inventory, customers, and orders in a business environment. This project was developed in **NetBeans IDE** as part of an internship at **Miamin Systems Inc.**

## ✅ Features

- 🔐 **User Management**
  - Login/logout functionality with role-based access control (Admin, Manager, Staff)

- 🧾 **Category Management**
  - Add, update, and delete product categories for better organization

- 📦 **Product Management**
  - CRUD operations for products with stock level tracking

- 🧑‍💼 **Customer Management**
  - Add and maintain customer information for order processing

- 🛒 **Order Processing**
  - Create and manage customer orders
  - Track status and generate receipts

- 📊 **View Orders**
  - View all past orders with detailed breakdowns
  - Search and filter by date, customer, or product

---

## 🏗️ System Architecture

Follows a **3-Tier Architecture**:
1. **Presentation Layer** – Java Swing (JFrame) for UI
2. **Business Logic Layer** – Java classes for operations and validation
3. **Data Layer** – MySQL database for structured and relational storage

---

## 🧰 Tech Stack

| Layer               | Technology       |
|--------------------|------------------|
| Frontend           | Java Swing (JFrame) |
| Backend            | Java              |
| Database           | MySQL             |
| IDE                | NetBeans          |

---

## 🗃️ Database Schema

Key tables include:

- `user` – Stores user credentials and roles  
- `category` – Product categories  
- `product` – Product details such as name, quantity, and price  
- `customer` – Customer information  
- `order` – Customer orders with status and date  
- `view_order` – Processed orders and their summaries  
- `logout` – Tracks user logout activities

---

## 🚀 Deployment Guide

1. Clone or download the project folder
2. Import into **NetBeans IDE**
3. Set up the **MySQL** database using the provided `.sql` file
4. Update database credentials in the project config (if applicable)
5. Run the project through NetBeans

---

## 🧪 Testing

- **Unit Testing**: Individual features tested during development
- **Integration Testing**: Ensured seamless interaction between UI and database
- **User Acceptance Testing (UAT)**: Application reviewed by internal users

---

## 🌟 Future Enhancements

- Barcode scanning support  
- Cloud integration for multi-branch inventory control  
- Intelligent restocking alerts using predictive analysis

---


