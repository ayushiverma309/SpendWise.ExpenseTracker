
<h1 align="center">🌟 My Wallet - Expense Tracking App 🌟</h1>

<p align="center">
  <img alt="Static Badge" src="https://img.shields.io/badge/Spring%20Boot-darkgreen?style=for-the-badge">
  <img alt="Static Badge" src="https://img.shields.io/badge/React.js-blue?style=for-the-badge">
  <img alt="Static Badge" src="https://img.shields.io/badge/mysql-red?style=for-the-badge">
  <img alt="Static Badge" src="https://img.shields.io/badge/css-purple?style=for-the-badge">
  <img alt="Static Badge" src="https://img.shields.io/badge/jwt-orange?style=for-the-badge">
</p>


A full-stack web application to efficiently manage and track your daily expenses and incomes. Built using **React.js**, **Spring Boot**, and **MySQL**, it allows users to log transactions, set budgets, and analyze financial behavior through intuitive dashboards and statistics.

Designed for individuals looking for a secure and seamless personal finance management solution with real-time tracking and admin monitoring capabilities.

---

## 📖 Table of Contents
- [📝 Project Description](#-project-description)
- [📂 Project Structure](#-project-structure)
- [⚙️ Tech Stack](#-tech-stack)
- [📦 Backend Dependencies](#-backend-dependencies)
- [🚀 Setup Instructions](#-setup-instructions)
- [✅ Features](#-features)
- [📸 Screenshots](#-screenshots)
- [🔮 Future Enhancements](#-future-enhancements)
- [👨‍💻 Author](#-author)

---

## 📝 Project Description

**My Wallet** helps users take control of their finances. From tracking everyday transactions to analyzing monthly spending patterns, this app provides the tools you need to budget wisely and make informed financial decisions.

Key features include:

- Multi-Role Authentication: Implemented multi-role functionality with user authentication, enabling secure access for both users and administrators, with features such as sign-in, sign-up, password reset, and email verification.
- User Management: Developed intuitive user dashboards, transaction management, upcoming/recurring transactions tracking, monthly summaries, and statistics, budget management.
- Categorized Transactions: Developed categories, users and transactions management for administrators.
- Admin Analytics: Implemented management capabilities including search, filter and pagination.

---

## 📂 Project Structure

```
Fullstack-Expense-Tracker/
├── backend/
│   ├── src/
│   ├── pom.xml
│   └── application.properties
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
```

---

## ⚙️ Tech Stack

### 🔧 Backend (Spring Boot)
- Java
- Spring Boot
- Spring Security
- JWT (JSON Web Token)
- MySQL
- JPA/Hibernate

### 🎨 Frontend (React)
- React.js
- Axios
- CSS

### 🗄️ Database
- MySQL

---

## 📦 Backend Dependencies (`pom.xml`)
- `spring-boot-starter-web`
- `spring-boot-starter-data-jpa`
- `spring-boot-starter-security`
- `mysql-connector-java`
- `jjwt` (JWT Authentication)
- `lombok`
- `spring-boot-starter-mail`
- `spring-boot-starter-validation`

---

## 🚀 Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/Fullstack-Expense-Tracker
```

### 2️⃣ Backend Setup

Update `application.properties` in `backend/src/main/resources`:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/YOUR_DATABASE
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD

spring.mail.username=YOUR_EMAIL
spring.mail.password=YOUR_EMAIL_PASSWORD
```

Run the backend:
```bash
./mvnw spring-boot:run
```
- It will auto-create required tables.
- Add category data manually for both expense and income.
- Insert an admin user manually in the `users` table to access admin features.

### 3️⃣ Frontend Setup
```bash
cd frontend
npm install
npm start
```

Open in browser: [http://localhost:3000](http://localhost:3000)

---

## ✅ Features
- 🔐 Secure Sign-up, Login & JWT Authentication  
- 🔄 Password Reset & Email Verification  
- 👥 Multi-role Access (Admin & Users)  
- 💳 Add/Edit/Delete Transactions  
- 📅 Recurring/Upcoming Transaction Management  
- 📊 Monthly Statistics & Budget Tracking  
- 🗂️ Admin Dashboard with User & Category Management  
- 🔍 Search, Filter, Pagination  

---

## 📸 Screenshots

![Screenshot 2024-04-18 091658](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/7637b70d-8b9f-485e-84f6-bce3c940f3f2)
![Screenshot 2024-04-18 091720](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/f58e2e13-7db4-439a-b371-ce9b6e5838c7)
![Screenshot 2024-04-18 091743](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/dbcfdbd2-d515-4197-b5ff-11ba0aed2dcf)
![Screenshot 2024-04-18 091803](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/9d271a52-1444-4739-afe4-f51aa616d55e)

### 🧑‍💼 User Dashboard

![Image](https://github.com/user-attachments/assets/55fae3c1-b132-4bb7-8bba-6f43d2aef680)
![Image](https://github.com/user-attachments/assets/aca5721c-c8f6-4d56-aa35-01e0deac7637)
![Image](https://github.com/user-attachments/assets/42ede346-8461-4ac3-ac7e-a78eaa2a7907)
![Image](https://github.com/user-attachments/assets/af01b9fa-6ec4-46e8-80bc-1f0f6f4d4b97)
![Image](https://github.com/user-attachments/assets/2ec57ead-16f5-46ad-8e47-1e38a57d736c)
![Screenshot 2024-04-22 154244](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/7e43cb13-6187-4af0-8900-66afef908f66)
![Screenshot 2024-04-22 154301](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/1b308447-f5ef-4f26-826b-0e9f42e5914f)

### 🛡️ Admin Dashboard

![Screenshot 2024-04-18 092306](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/a024fadc-5f6a-4e3f-96f6-f38dd1f6b477)
![Screenshot 2024-04-18 092325](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/5e93095e-f4be-4245-b3a4-8653cd9fea27)
![Screenshot 2024-04-18 092342](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/5d40498e-ec3b-4559-ba15-efdf9c248d22)
![Screenshot 2024-04-18 092805](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/aa94d2da-0080-421b-a191-d2ff9fb4472f)
![Screenshot 2024-04-18 092822](https://github.com/DharshiBalasubramaniyam/Fullstack-Expense-Tracker/assets/139672976/6cb49c2c-8317-4cec-ad16-b9496d97b16f)

---

## 🔮 Future Enhancements
- 📲 Mobile App Integration (React Native)  
- 📤 Export Transactions (PDF/CSV)  
- 💡 AI-powered Expense Suggestions  
- 🔔 Smart Budget Alerts  
- 🌍 Multi-language Support  

---

## 👨‍💻 Author

**Ayushi Verma** 

📧 Email **ayushiverma309@gmail.com** 

🌐 GitHub **https://github.com/ayushiverma309**
