#  E-Commerce Management System (Python + MySQL)

This is a terminal-based E-commerce Order Processing System developed using Python and MySQL.  
It allows customers to register, manage products, use a cart, and place/view orders.  
The project demonstrates:

- Object-Oriented Programming (OOP)
- Data Access Object (DAO) Pattern
- Custom Exceptions
- MySQL Integration
- Unit Testing
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

- **Language**: Python 
- **Database**: MySQL
- **Tools**: VS Code,Mysql
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

