# 🛒 Quick Mart – E-commerce Application

Quick Mart is a full-featured **e-commerce web application** that enables users to
browse products, add items to a cart, and securely complete purchases.
It also provides an **admin dashboard** for managing products, users, and orders.

---

## 🚀 Features

### 👤 User Features
- User authentication (Sign up & Login)
- Browse products by category
- Search products by name or filters
- Add and remove products from cart
- Secure checkout and payment integration
- View order history

### 🛠️ Admin Features
- Admin authentication
- Add, update, and delete products
- Manage users
- View and manage customer orders
- Update order status (shipped / completed)

---

## 🧰 Tech Stack

### Frontend
- React.js (Vite)
- React Hooks & Context API
- React Router
- Tailwind CSS

### Backend
- Node.js
- Express.js
- MongoDB (Local Database)
- JWT Authentication

### Other Tools
- Stripe API (Payment Gateway)
- Git & GitHub

---


---

## ⚙️ Installation & Setup

### ✅ Prerequisites
Ensure you have the following installed:

- Node.js (v14 or higher)
- MongoDB (running locally)
- Stripe account (for payment testing)

---

### 📥 Clone the Repository

```bash
git clone https://github.com/ashutosh0203/QuickMart.git
cd Quick-Mart

### 📦 Install Dependencies

#### Frontend

```bash
cd frontend
npm install
```

#### Backend

```bash
cd backend
npm install
```

---

### 🚀 Running the Application

Run both backend and frontend concurrently:

```bash
npm run dev
```

---

## 📱 Usage

Once both servers are running:

- Browse products
- Add products to the cart
- Sign up and log in to make purchases
- Proceed to checkout and enter payment details
- Access admin dashboard for:
  - Managing products
  - Managing users
  - Tracking and updating orders

---

## 📌 Note

This project uses **MongoDB locally** for development.  
➡️ Ensure your **MongoDB service is running** before starting the backend server.