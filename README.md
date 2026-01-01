🏦 Banking Management System (Core Java)

A console-based Banking Management System developed using Core Java and MySQL.
This project simulates basic banking operations such as account creation, login, deposits, withdrawals, balance inquiry, and fund management.

📌 Features

User Registration & Login

Create Bank Account

Deposit Money

Withdraw Money

Check Account Balance

View Account Details

MySQL Database Integration

Console-based Menu-driven Application

🛠️ Tech Stack
Technology	Description
Java	Core Java (JDK 8+)
Database	MySQL
IDE	IntelliJ IDEA / Eclipse
JDBC	MySQL Connector
📂 Project Structure
Banking-Management-System
│
├── src/
│   └── BankingManagementSystem/
│       ├── BankingApp.java        # Main class (Application Entry Point)
│       ├── AccountManager.java    # Business logic for banking operations
│       ├── Accounts.java          # Account entity class
│       └── User.java              # User entity class
│
├── Database Schema.png             # Database design
├── README.md
└── .idea/                          # IDE configuration files

⚙️ Database Setup

Create a MySQL database:

CREATE DATABASE banking_system;


Create required tables (sample structure):

CREATE TABLE users (
    user_id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    email VARCHAR(100),
    password VARCHAR(100)
);

CREATE TABLE accounts (
    account_id INT AUTO_INCREMENT PRIMARY KEY,
    user_id INT,
    balance DOUBLE,
    FOREIGN KEY (user_id) REFERENCES users(user_id)
);


Update your database credentials in the code (JDBC connection).

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/your-username/Banking-Management-System.git


Open the project in IntelliJ / Eclipse

Add MySQL Connector JAR to your project:

mysql-connector-j-8.1.0.jar


Configure database connection in code

Run:

BankingApp.java

🖥️ Application Flow

User Registration

User Login

Banking Menu:

Deposit

Withdraw

Check Balance

View Account Details

Exit

📸 Screenshots

Database Schema included as Database Schema.png

🚀 Future Enhancements

GUI using JavaFX or Swing

Transaction History

Admin Panel

Password Encryption

Exception Handling Improvements

REST API using Spring Boot

👨‍💻 Author

R Rohit
Java Developer
📧 Feel free to connect for suggestions or improvements

📄 License

This project is for learning and educational purposes.
