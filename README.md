# Microfinance Loan Management System 💼

A full-stack web application for managing microfinance operations with **React frontend** and **Node.js backend**.  
It provides a complete workflow for borrowers, loan processing, repayments, and analytics.

---

## 🎥 Demo Video

[![Project Demo](https://img.youtube.com/vi/AEvAwIRPoZE/0.jpg)](https://www.youtube.com/watch?v=AEvAwIRPoZE)

---

## 📱 Features

- 👤 User authentication (Admin / Staff)  
- 👥 Borrower management  
- 💰 Loan processing & tracking  
- 📅 EMI calculations  
- 💵 Repayment management  
- 📊 Analytics dashboard  

---

## 🔐 Default Logins

- **Admin:** admin / admin123  

---

## 🚀 Quick Setup

### 1. Clone & Install

```bash
git clone https://github.com/ritikaseth1003/Microfinance_Loan_Management.git
cd Microfinance_Loan_Management

# Install backend
cd microfinance-backend
npm install

# Install frontend
cd ../microfinance-frontend
npm install
```
## 2. Database Setup

- Open `MICROFINANCE_DB.sql` in a text editor  
- Copy all the SQL code  
- Open **MySQL Workbench** → New query tab  
- Paste and run:

```sql
CREATE DATABASE microfinance_db;
USE microfinance_db;
-- Paste rest of SQL code here
```
## 3. Configure Backend
```
Create a .env file inside microfinance-backend/:

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=microfinance_db
PORT=5000
JWT_SECRET=any_random_string_here
```
## 4. Run the Application

Open two terminals:
```bash
Backend:

cd microfinance-backend
npm start
# Runs on http://localhost:5000



Frontend:

cd microfinance-frontend
npm start
# Runs on http://localhost:3000
```
⭐ Support

If you find this project useful, please give it a ⭐ on GitHub!
