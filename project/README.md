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
---

## Setup Instructions

### 1. MySQL Setup

```sql
CREATE DATABASE ecommerce;
```

Create tables manually or let the DAO class generate them via queries.

### 2. Configure DB

In `util/db.properties`:

```
host=localhost
port=3306
user=root
password=Mathavan@003
database=ecommerce
```

### 3. Run the App

```bash
python app/EcomApp.py
```

### 4. Run Unit Tests

```bash
python -m unittest test/test_cases.py
```

---

## Database Tables

- customers
- products
- cart
- orders
- order_items

Uses foreign key relationships and basic CRUD operations.

---


## Conclusion

This project showcases a complete E-commerce system developed using core Python and MySQL technologies. 
It emphasizes clean coding principles including OOP, DAO, exception handling, and modular design. 
With unit testing and structured database interaction, this application provides a solid foundation for future upgrades 
such as adding a GUI or converting to a web application using Flask or Django.

This solution is robust, easy to maintain, and well-suited for both academic submission and real-world use cases.

