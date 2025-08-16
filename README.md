# 🛒 Simple Grocery Store (Python OOP Example)

This is a simple **command-line Grocery Store application** built with Python.  
It demonstrates **Object-Oriented Programming (OOP)** concepts and **exception handling** using `try-except`.

---

## 🚀 Features
- **Product Class** – Represents each grocery item (ID, Name, Price).  
- **Store Class** – Manages available products and product lookup.  
- **Cart Class** – Lets users add items and calculates the total.  
- **Error Handling** – Uses `try-except` to handle invalid input.  
- **Interactive CLI** – Users can select products, choose quantity, and checkout.  

---

## 🏗️ OOP Concepts Used
1. **Encapsulation** – Products, Store, and Cart are defined as classes.  
2. **Abstraction** – Methods like `add_product()`, `show_products()`, `add_to_cart()` hide internal logic.  
3. **Polymorphism (basic)** – `__str__` method in `Product` class customizes how products are displayed.  
4. **Composition** – `Store` contains `Product` objects, and `Cart` contains both `Product` and quantity.  

---

## 📂 Project Structure
