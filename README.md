# Personal_-Expense-_Tracker-
Personal Expense Tracker is an application used to manage daily income and expenses. It helps users record transactions, track spending, and maintain a budget easily. The system stores expense details and shows reports to help users manage their money effectively.
# Personal Expense Tracker

## Abstract
Personal Expense Tracker is a web-based application used to manage daily income and expenses efficiently. The system helps users record financial transactions, monitor spending habits, and maintain a monthly budget. Users can add, edit, delete, and view expense details easily. The application provides reports and summaries to help users understand where their money is spent.

---

## Project Overview
The Personal Expense Tracker is designed to simplify financial management. This application provides a digital solution where users can securely store expense records and analyze their spending patterns. The system improves budgeting and reduces unnecessary expenses.

---

## Problem Statement
Managing expenses manually using notebooks or spreadsheets is difficult and time-consuming. Users may forget transactions, lose records, or fail to maintain proper budgets. There is a need for a simple and efficient system to track expenses digitally and generate reports automatically.

---

## Objective
- To manage daily income and expenses
- To maintain financial records digitally
- To reduce unnecessary spending
- To generate monthly expense reports
- To provide a user-friendly expense management system

---

## Features
- Add income and expense details
- Edit and delete transactions
- Category-wise expense tracking
- Monthly expense reports
- User login and authentication
- Dashboard for expense summary
- Budget management
- Simple and responsive interface

---

## Modules

### User Module
- User Registration
- User Login
- Profile Management

### Expense Module
- Add Expenses
- Edit Expenses
- Delete Expenses
- View Expense History

### Income Module
- Add Income
- View Income Details

### Report Module
- Monthly Reports
- Expense Summary
- Budget Analysis

### Admin Module
- Manage Users
- View System Reports

---

## Technologies Used

### Front End
- HTML
- CSS
- JavaScript
- Bootstrap

### Back End
- Python / PHP

### Database
- MySQL

### Tools
- VS Code
- GitHub
- XAMPP

---

## Technology Stack

| Layer | Technology |
|-------|-------------|
| Front End | HTML, CSS, JavaScript |
| Back End | Python / PHP |
| Database | MySQL |
| Version Control | GitHub |
| IDE | VS Code |

---

## Database Tables

### User Table

| Field Name | Type |
|------------|------|
| user_id | INT |
| username | VARCHAR |
| email | VARCHAR |
| password | VARCHAR |

### Expense Table

| Field Name | Type |
|------------|------|
| expense_id | INT |
| user_id | INT |
| category | VARCHAR |
| amount | FLOAT |
| date | DATE |
| description | TEXT |

### Income Table

| Field Name | Type |
|------------|------|
| income_id | INT |
| user_id | INT |
| source | VARCHAR |
| amount | FLOAT |
| date | DATE |

---

## ER Diagram

USER → EXPENSE  
USER → INCOME

User Table:
- user_id
- username
- email
- password

Expense Table:
- expense_id
- user_id
- category
- amount
- date
- description

Income Table:
- income_id
- user_id
- source
- amount
- date

---

## Use Case Diagram

User can:
- Login
- Add Expense
- Add Income
- View Reports
- Manage Budget
- Logout

---

## Expected Outcome
- Easy expense management
- Accurate financial tracking
- Better budgeting system
- Reduced unnecessary expenses
- Secure data storage
- Quick generation of reports


---

## Front End Details
The front end of the Personal Expense Tracker provides a simple and user-friendly interface for users to interact with the application. Users can easily add expenses, view reports, manage budgets, and monitor financial records through responsive web pages.

---

## Back End Details
The back end handles the business logic, database connectivity, and transaction processing of the application. It stores user data securely, processes expense records, and generates reports for efficient financial management.

---

## Advantages
- Easy to use
- Saves time
- Improves financial planning
- Secure data management
- Reduces manual calculation errors

---

## Conclusion
The Personal Expense Tracker is an efficient application for managing daily financial activities. It helps users track expenses, maintain budgets, and analyze spending habits effectively. The project improves financial awareness and simplifies expense management through digital technology.
