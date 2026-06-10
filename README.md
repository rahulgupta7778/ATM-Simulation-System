# 🏦 Bank ATM Simulation System

A comprehensive console-based ATM Simulation System developed in **Java** that replicates core banking and ATM operations using **file handling, authentication mechanisms, transaction management, role-based access control, and persistent data storage**.

The system features separate **Customer** and **Administrator** modules, allowing secure banking operations while maintaining transaction records and ATM cash management.

---

# ✨ Features

## 👤 Customer Module

* Secure account login using Account Number and PIN
* Account locking after multiple failed login attempts
* Cash withdrawal facility
* Real-time balance inquiry
* Transaction history generation
* Date and time stamped transaction records

## 👨‍💼 Administrator Module

* Secure administrator authentication
* Hidden administrative access panel
* ATM cash refill management
* ATM balance monitoring
* User account status management
* ATM administrative transaction tracking

---

# 💾 File Handling

The project uses text files for persistent data storage and transaction management.

### Files Used

| File Name                 | Purpose                                                         |
| ------------------------- | --------------------------------------------------------------- |
| `userInfo.txt`            | Stores user account details, PINs, balances, and account status |
| `transactionHistory.txt`  | Stores customer transaction records                             |
| `atmTotalMoney.txt`       | Maintains current ATM cash balance                              |
| `atmAdminTransaction.txt` | Stores ATM refill and administrative activities                 |
| `adminInfo.txt`           | Stores administrator credentials                                |

---

# 🔐 Security Features

The system incorporates multiple security measures to simulate real-world ATM operations:

* PIN-based authentication
* Login attempt tracking
* Automatic account locking after repeated failed attempts
* Account status verification (ACTIVE / LOCKED)
* Restricted administrative access
* Role-based operation control

---

# 💳 Banking Operations

### Customer Transactions

* Cash Withdrawal
* Balance Inquiry
* Transaction Receipt Generation
* Transaction History Viewing

### ATM Operations

* ATM Cash Refill
* ATM Cash Balance Updates
* Administrative Activity Logging

---

# 📋 Transaction Logging

Every financial transaction is automatically recorded with:

* Account/Admin ID
* Transaction Type
* Transaction Amount
* Updated Balance
* Date & Time Stamp

This provides complete transaction traceability and audit history.

---

# ⚠️ Validation & Error Handling

The project includes extensive validation and exception handling:

* Invalid account number detection
* Incorrect PIN handling
* Maximum login attempt enforcement
* Account lock detection
* Invalid withdrawal amount prevention
* Insufficient account balance handling
* Insufficient ATM cash handling
* File access error handling
* Transaction record validation
* Administrative operation validation

---

# 🧠 Concepts Used

* Object-Oriented Programming (OOP)
* File Handling
* Exception Handling
* Collections Framework (`ArrayList`)
* Authentication Systems
* Role-Based Access Control
* Input Validation
* Transaction Processing Logic
* Date & Time API (`LocalDateTime`)
* Console-Based User Interface Design

---

# 🛠️ Technologies Used

* Java
* Java Collections Framework
* Java File Handling APIs
* Java Time API
* BufferedReader & BufferedWriter
* Scanner Class

---

# 🚀 How to Run

## Compile the Program

```bash
javac ATM_SIMULATION.java
```

## Run the Program

```bash
java ATM_SIMULATION
```

---

# 📁 Required Files

Ensure the following files are present in the project directory before execution:

* `userInfo.txt`
* `transactionHistory.txt`
* `atmTotalMoney.txt`
* `atmAdminTransaction.txt`
* `adminInfo.txt`

---

# 🎯 Learning Outcomes

This project helped in understanding practical implementations of:

* Banking System Logic
* User Authentication Mechanisms
* File-Based Database Simulation
* Transaction Management Systems
* Administrative Control Systems
* Exception Handling Strategies
* Data Persistence Techniques
* Real-World Console Application Development

---

# 👨‍💻 Developed By

## Rahul Gupta
---

# 📖 Project Overview

This project was developed as a practical implementation of a real-world ATM Banking System using Java. The objective was to simulate secure banking operations while gaining hands-on experience in file handling, authentication systems, transaction processing, data persistence, and software design principles.

The project demonstrates how core Java concepts can be applied to build a complete banking application without relying on external databases, making it an excellent learning exercise in software development and system design.
