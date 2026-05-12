# ☕ Cafe Management System

A Java Swing based desktop application for managing a cafe shop. This project includes product management, employee authentication, signup/login system, image upload support, and MySQL database integration.
This project was developed as a Group Project during our **Object Oriented Programming (OOP) Lab Course**.


---

# 📌 Features

## 🔐 Authentication System
- Employee Signup
- Employee Login
- Password Visibility Toggle
- Input Validation
- Duplicate Username/Email/Phone Detection

---

## 🛍 Product Management
- Add Products
- Update Products
- Delete Products
- Upload Product Images
- Product Categories
- Product Description & Pricing

---

## 🖼 Image Handling
- Upload product images using `JFileChooser`
- Preview uploaded image
- Store image path in MySQL database

---

## 🗂 Categories
Products can be categorized into:
- Refreshments
- Warmers
- Quickbites
- Beverage
- Sandwich
- Desserts

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Java | Core Programming |
| Java Swing | GUI Development |
| MySQL | Database |
| JDBC | Database Connectivity |
| NetBeans IDE | Development Environment |

---

# 🧩 Object-Oriented Programming (OOP) Concepts Used

This project implements the four main OOP principles as follows:

## 🧱 1. Encapsulation
- All UI components and data fields (e.g., product details, user credentials) are encapsulated inside their respective classes.
- Data is accessed and modified through methods such as button event handlers (`addActionPerformed`, `signUpActionPerformed`, etc.).
- This helps in protecting data and controlling access within the application.

## 🧬 2. Abstraction
- Internal implementation details like JDBC database connection, SQL queries, and file handling are hidden from the user.
- The user interacts only with simple actions like Add, Update, Delete, and Sign Up.
- Complexity is reduced by separating UI actions from backend logic.

## 🧱 3. Inheritance
- Built-in inheritance is used through Java Swing classes.
- Example:  
  - `JFrame` is inherited by all GUI classes such as `Login`, `Signup`, and `Product`.
- This allows reuse of pre-built GUI functionality.

## 🧩 4. Polymorphism
- Achieved through event handling mechanisms in Java Swing.
- Methods like `actionPerformed()` are used for different buttons and components, showing different behaviors based on user interaction.
- Event listeners demonstrate runtime polymorphism.

---
# 🧠 Learning Outcomes

This project demonstrates:

- Java Swing GUI Development  
- Event Handling  
- JDBC Integration  
- CRUD Operations  
- File Handling  
- Regex Validation  
- Image Processing  