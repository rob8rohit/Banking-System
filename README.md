# 🏦 Smart Banking System – Java Full Stack Project

A **full-stack banking management system** built using **Java, Spring Boot, MySQL, HTML, CSS, and JavaScript**.  
This project demonstrates real-world banking operations such as account creation, balance management, and data persistence using RESTful APIs.

---

## 🚀 Features

- Create bank accounts
- View all bank accounts
- REST API based backend
- Spring Boot + JPA (Hibernate)
- MySQL database integration
- Simple frontend using HTML & JavaScript
- MVC layered architecture
- Ready to extend with authentication & transactions

---

## 🧰 Tech Stack

### Backend
- Java 17
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate
- MySQL

### Frontend
- HTML5
- JavaScript (Fetch API)

### Tools
- IntelliJ / Eclipse
- Maven
- MySQL Workbench
- Postman
- Git & GitHub

---

## 🏗️ Project Structure

Smart-Banking-System
│
├── backend
│ ├── src/main/java/com/example/banking
│ │ ├── controller
│ │ ├── model
│ │ ├── repository
│ │ ├── service
│ │ └── BankingApplication.java
│ │
│ ├── src/main/resources
│ │ ├── static
│ │ │ └── index.html
│ │ └── application.properties
│ │
│ └── pom.xml
│
└── README.md

yaml
Copy code

---

## 🗄️ Database Configuration

Create MySQL database:

```sql
CREATE DATABASE banking_db;
Update credentials in application.properties:

properties
Copy code
spring.datasource.url=jdbc:mysql://localhost:3306/banking_db
spring.datasource.username=root
spring.datasource.password=root

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
▶️ How to Run the Project
Step 1️⃣
Extract the ZIP file

Step 2️⃣
Open the backend folder in IntelliJ / Eclipse

Step 3️⃣
Run the application:

bash
Copy code
BankingApplication.java
Step 4️⃣
Open browser:

bash
Copy code
http://localhost:8080/index.html
🌐 REST API Endpoints
➕ Create Account
bash
Copy code
POST /api/accounts
Request Body

json
Copy code
{
  "name": "Rohit",
  "balance": 5000
}
📄 Get All Accounts
bash
Copy code
GET /api/accounts
🖥️ Frontend UI
Simple account creation form

Displays all accounts dynamically

Uses Fetch API to communicate with backend

🔐 Future Enhancements
User registration & login

JWT authentication

Deposit / Withdraw money

Fund transfer between accounts

Transaction history

Admin dashboard

Thymeleaf or React frontend

PDF account statements

Docker deployment

🎯 Interview Concepts Covered
Spring Boot architecture

REST API design

JPA & Hibernate

MVC pattern

Dependency Injection

Database relationships

Full-stack integration

👨‍💻 Author
R Rohit
Java | Spring Boot | Full Stack Developer
