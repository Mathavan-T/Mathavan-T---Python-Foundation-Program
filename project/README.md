# 🛒 E-Commerce Management System (Python + MySQL)

This is a console-based E-commerce management system built using Python and MySQL. It allows users to browse products, manage a shopping cart, and place orders, while admins can manage inventory and view order details.
---

## 📌 Features

- User Registration & Login
- Product Catalog Management
- Shopping Cart System
- Order Placement & History
- Admin Dashboard (Add/Delete Products)
- Database integration using DAO Pattern
- Proper use of Custom Exceptions and Utility Classes

---

## 🛠️ Tech Stack

- **Language**: Python 3.x
- **Database**: MySQL (via XAMPP)
- **Tools**: VS Code, GitHub
- **Architecture**: OOP, DAO Pattern

---

## 📂 Project Structure

```bash
ecommerce_project.zip
├── dao/
│   └── product_dao.py
│   └── user_dao.py
├── models/
│   └── product.py
│   └── user.py
├── services/
│   └── ecommerce_service.py
├── utils/
│   └── db_connection.py
│   └── custom_exceptions.py
├── main.py
└── README.md
