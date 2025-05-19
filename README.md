# 📚 Library Management System – DBMS Mini Project

This is a **Relational Database Management System (RDBMS)** project designed to manage operations of a typical library. Built using **MySQL**, the system supports tracking of books and videos, handling user registrations, rental operations, and fine calculation.

---

## 🛠️ Technologies Used
- **MySQL** – For relational database design and queries
- **ER Diagram** – For conceptual modeling
- **SQL Procedures & Constraints** – To enforce business logic and data integrity

---

## 🎯 Objectives
- Develop a normalized relational schema for a Library Management System
- Support customer and employee data management
- Track rentals, returns, fines, and item availability
- Implement role-based access control for secure usage
- Maintain data integrity with constraints, validations, and stored procedures

---

## 🧩 Key Features
- Register customers and employees
- Issue and return books/videos
- Track delays, calculate fines, and manage lost items
- Store and retrieve user, item, and branch information
- Enforce one-to-many and many-to-one relationships using foreign keys

---

## 📌 ER Diagram Overview
Entities include:
- **PERSON** (general info)
- **CUSTOMER** and **EMPLOYEE** (subtypes of PERSON)
- **ITEM**, **BOOK**, **VIDEO**
- **CARD**, **RENT**, **BRANCH**, **LOCATION**, and relationships like **WORK**, **SITUATED**

*(ER Diagram image goes here)*  
https://github.com/jahnavii-25/Library-Management-System/blob/main/ER%20DIAGRAM.jpg

---

## 🗃️ Database Schema Highlights
- `PERSON (ID, Name, Address, Phone, Card_no, Username, Password)`
- `CUSTOMER (ID, Date_Signup)`
- `EMPLOYEE (ID, Paycheck)`
- `ITEM (ID, Type, Availability, State, Delay_Cost, Lost_Cost)`
- `BOOK (ID, ISBN)`
- `VIDEO (ID, Title, Year)`
- `RENT (Card_no, Item_ID, Date, Return_Date)`
