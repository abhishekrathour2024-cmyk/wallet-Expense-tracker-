# 💰 Personal Expense Tracker (Wallet Backend)

A backend application built using Java and Spring Boot to manage users, wallets, and financial transactions. This system enables users to track expenses, manage balances, and perform transaction operations through RESTful APIs.

---

## 🚀 Features

- Developed **18 RESTful APIs** for user, wallet, and transaction management  
- Wallet-based expense tracking system  
- CRUD operations for users, wallets, and transactions  
- Maintains user-wise financial data and balance tracking  
- Input validation using **Jakarta Bean Validation**  
- Global exception handling for consistent API responses  
- API documentation using **Swagger (OpenAPI)**  

---

## 🏗️ Architecture

The project follows a layered architecture:

Controller → Service → Repository → Entity

- **Controller** → Handles HTTP requests  
- **Service** → Contains business logic  
- **Repository** → Handles database operations  
- **Entity** → Represents database tables  

---

## 🛠️ Tech Stack

- Java 17  
- Spring Boot  
- Spring Data JPA (Hibernate)  
- MySQL  
- REST APIs  
- Swagger (OpenAPI)  
- Lombok  
- Jakarta Bean Validation  

---

## 📌 API Overview

### 👤 User APIs
- Create User  
- Get User by ID  
- Get All Users  
- Update User  
- Delete User  

### 💼 Wallet APIs
- Create Wallet  
- Get Wallet Details  
- Update Wallet  
- Delete Wallet  

### 💳 Transaction APIs
- Add Transaction (Income / Expense)  
- Get Transaction by ID  
- Get All Transactions  
- Update Transaction  
- Delete Transaction  

---

## 📷 API Documentation

Access Swagger UI at:

http://localhost:8080/swagger-ui/index.html

---

## ⚙️ Setup & Installation

### 1. Clone Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
