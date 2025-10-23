# 🏦 BankLite – Console Banking System

## 📘 Overview
**BankLite** is a simple **Python console-based banking system** that simulates basic bank operations.  
Users can create accounts, deposit or withdraw money, view balances, and check transaction history — all stored in a JSON file.

This project demonstrates the fundamentals of **Object-Oriented Programming (OOP)**, **file handling**, and **data persistence** in Python.

---

## 🎯 Features
✅ Create a new bank account  
✅ Deposit and withdraw funds  
✅ View account balance  
✅ View transaction history  
✅ Save and load account data from `bank.json`

--------------------------
## ⚙️ How It Works
--------------------------
### 1️⃣ Account Class
Handles individual user accounts.

**Attributes:**
- `id` – Unique account ID  
- `name` – Account holder’s name  
- `balance` – Current balance  
- `transactions` – List of transaction strings  

**Methods:**
- `deposit(amount)` – Adds funds  
- `withdraw(amount)` – Deducts funds (if balance is sufficient)  
- `get_balance()` – Returns current balance  
- `get_history()` – Returns transaction history  
- `to_dict()` / `from_dict()` – Converts data for JSON storage  

---

### 2️⃣ Bank Class
Manages multiple accounts and file storage.

**Methods:**
- `create_account(name, balance)`  
- `find_account_by_id(account_id)`  
- `deposit_to_account(account_id, amount)`  
- `withdraw_from_account(account_id, amount)`  
- `show_account_details(account_id)`  
- `save_to_file()` / `load_from_file()`  

---

## 💻 How to Run the Project

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/BankLite_project.git
cd BankLite_project
