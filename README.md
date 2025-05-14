# 🏠 Real Estate Management Platform

A full-stack real estate platform built with React.js and Spring Boot. It includes secure user authentication with JWT and Two-Factor Authentication (2FA), along with integrated Razorpay payment functionality.

---

## 📁 Project Structure
---

## 💻 Frontend – `HousingHeights/`

The `HousingHeights` folder contains the complete frontend code for the platform, developed using **React.js**.

### 🔨 Key Features:
- 🏘️ Property listing and browsing
- 🔐 User registration and login functionality
- 📱 Fully responsive design (mobile-friendly)
- 💳 Seamless payment handling via Razorpay (triggered from frontend)
- ⚡ Fast navigation and interactive UI using React Router

---

## 🔧 Backend – `realestate-mgmt/`

The `realestate-mgmt` folder contains the backend implementation using **Spring Boot**.

### 🔐 Security:
- ✅ JWT-based authentication for session security
- 🔒 Two-Factor Authentication (2FA) for an added layer of protection
- 👥 Role-based access control (Admin/User)

### 💳 Payment Integration:
- Integrated **Razorpay Payment Gateway**
- Complete flow from order creation to payment confirmation
- Secure API endpoints for transactions

### 🧰 Tech Stack:
- Java 17
- Spring Boot
- Spring Security
- JWT
- MySQL
- Razorpay Java SDK
- Maven

---
## 🚀 Getting Started

Follow the steps below to set up and run both the frontend and backend of the Real Estate Management Platform on your local machine.

---

### 🧪 Backend Setup – `realestate-mgmt/`

1. **Navigate to the backend project folder**:
   ```bash
 Configure the application.properties file (located in src/main/resources/) with your database and Razorpay credentials:
 Make sure MySQL is running, and the specified database is created.

Run the application using Maven:
🌐 Frontend Setup – HousingHeights/
Navigate to the frontend project folder:
Install all required npm packages:
