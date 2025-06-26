#  E-Commerce Management System (Python + MySQL)

This is a console-based E-commerce management system built using Python and MySQL. It allows users to browse products, manage a shopping cart, and place orders, while admins can manage inventory and view order details.
---

##  Features

- User Registration & Login
- Product Catalog Management
- Shopping Cart System
- Order Placement & History
- Admin Dashboard (Add/Delete Products)
- Database integration using DAO Pattern
- Proper use of Custom Exceptions and Utility Classes

---

##  Tech Stack

- **Language**: Python 3.x
- **Database**: MySQL (via XAMPP)
- **Tools**: VS Code, GitHub
- **Architecture**: OOP, DAO Pattern

---

##  Project Structure

```bash
ecommerce_project/
│
├── app/
│   └── EcomApp.py
│
├── dao/
│   ├── OrderProcessorRepository.py
│   └── OrderProcessorRepositoryImpl.py
│
├── entity/
│   ├── Customer.py
│   ├── Product.py
│   ├── Cart.py
│   ├── Order.py
│   └── OrderItem.py
│
├── util/
│   ├── DBConnUtil.py
│   └── DBPropertyUtil.py
│   └── db.properties
│
├── myexceptions/
│   ├── CustomerNotFoundException.py
│   ├── ProductNotFoundException.py
│   └── OrderNotFoundException.py
│
├── test/
│   └── test_cases.py

