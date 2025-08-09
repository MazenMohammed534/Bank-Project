## Overview
The Bank Management System is a C++ console-based application designed to handle client accounts, user management, and financial transactions with a permission-based access control system.
It supports operations for administrators and staff, ensuring secure and organized banking operations.

---

## ✨ Features
**1. Client Management**
Add clients with unique account numbers

Delete client accounts

Update client information

Search clients by account number

Display all clients with details

---

**2. User Management (Admin)**
Add new system users with custom permissions

Delete existing users (Admin cannot be deleted)

Update user information and permissions

Search users by username

List all users

---

**3. Transactions**
Deposit funds to client accounts

Withdraw funds with balance validation

View total bank balance across all accounts

---

**4. Security & Access Control**
Login system with username/password authentication

Permission-based access:

Admin user has full permissions

Other users have granular access

## 🛠 Technical Details

**Data Storage**
Clients.txt → Stores client data

Users.txt → Stores user data

Data saved in text format using #//# delimiter

---

**Code Structure**
Object-Oriented Design (struct-based)

Modular functions for each feature

Menu-driven interface

Input validation for critical operations

---

## 🚀 How to Use
**1. Login**
Default Admin credentials:
Login is required before accessing the main menu.

**2. Main Menu**
Options displayed based on user permissions.

**3. Navigation**
Follow on-screen prompts

Press any key to return to previous menus

---

## 📦 Requirements
C++ compiler (tested with g++)

Standard C++ libraries

Console environment

---

## ⚠ Limitations
Text-based interface (no GUI)

Basic error handling

No password encryption

No transaction history/audit log

---

## 🔮 Future Enhancements
Password encryption

Transaction history tracking

Reporting and analytics

Improved UI with colors and formatting

Automatic data backup

