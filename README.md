# 🛒 E-Commerce Web Application (Spring Boot + React)

<p align="center">
  <img src="https://img.shields.io/badge/Spring--Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Stripe-626CD9?style=for-the-badge&logo=stripe&logoColor=white" />
  <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens" />
</p>

---

A robust full-stack E-Commerce platform built using **Spring Boot (Java)** for the backend and **React (Vite)** for the frontend.  
This application supports **Admin, Seller, and Customer roles**, featuring complete product management, secure authentication, and integrated payments.

---

## 🚀 Key Features

### 🔐 Authentication & Security
* **JWT-based Authentication**: Secure and stateless communication.
* **Role-Based Access Control (RBAC)**:
  * 👑 **Admin**: Full system oversight.
  * 🏢 **Seller**: Inventory and product management.
  * 🛍️ **Customer**: Seamless shopping experience.
* **Security**: Secure login/signup and cookie-based session handling.

### 👨‍💼 Admin Panel
* **Category Management**: Full CRUD (Add / Update / Delete) for store categories.
* **Product Oversight**: View and monitor all products platform-wide.
* **User Management**: Manage permissions for users and sellers.
* **Analytics**: Business insights via the dashboard.

### 🛍️ Seller Panel
* **Product Lifecycle**: Add, update, and delete products easily.
* **Inventory Control**: Real-time management of stock levels.
* **Self-Service**: View and manage your own product catalog.

### 👤 Customer Experience
* **Discovery**: Browse and search products across categories.
* **Shopping Cart**: Intuitive add-to-cart functionality.
* **Checkout**: Streamlined checkout system with order history.

### 💳 Secure Payments
* **Stripe Integration**: Industry-standard payment processing.
* **Secure Flow**: Professional checkout using client-side secrets.
* **Real-time Processing**: Immediate transaction feedback.

---

## 🧰 Tech Stack

| Layer | Technologies Used |
| :--- | :--- |
| **Frontend** | React.js (Vite), Redux (State Management), Axios, React Hook Form, Tailwind CSS |
| **Backend** | Java Spring Boot, Spring Security, JWT Authentication, Hibernate / JPA |
| **Database** | PostgreSQL |
| **Payment** | Stripe API |

---

## 📁 Project Structure

```text
.
├── sb-ecom (Backend)
│   ├── src/main/java      # Business logic & Controllers
│   ├── src/main/resources # Configurations (application.properties)
│   └── pom.xml            # Maven Dependencies
│
└── ecom-frontend (Frontend)
    ├── src/components     # Reusable UI components
    ├── src/store          # Redux state management
    ├── src/api            # Axios service layers
    └── tailwind.config.js # Styling configurations
