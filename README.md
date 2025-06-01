# 🏦 Banking System - Java OOP Project

This Java application models a simple banking system with customers, accounts, ATMs, and technicians. It demonstrates core object-oriented principles including encapsulation, composition, and basic transaction operations.

---

## ⚙️ Features

- **Customer** can hold multiple **Accounts** (up to 5).
- **Account** supports deposit and withdrawal with balance checks.
- **ATM** tracks cash availability and status.
- **ATMTechnician** can perform maintenance and repairs on ATMs.

---

## 📂 Class Overview

### Core Classes

| Class         | Description                                                                                 |
|---------------|---------------------------------------------------------------------------------------------|
| `Bank`        | Represents the bank entity with ID, name, address, phone, and IFSC code                      |
| `Customer`    | Stores customer details and manages their accounts                                          |
| `Account`     | Represents bank accounts with account number, type, balance, and opened date                |
| `Transaction` | (Skeleton) Records transaction details such as ID, type, amount, date, and status           |
| `ATM`         | Models an ATM machine with ID, location, status, and available cash                          |
| `ATMTechnician` | Represents technicians who maintain and repair ATMs                                      |

---

## 🖥 How to Run

1. Save all classes in a single file named `BankingSystem.java` (or split as needed).
2. Compile and run:

```bash
javac BankingSystem.java
java BankingSystem
