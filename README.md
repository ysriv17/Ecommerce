# 🛍️ E-Commerce Web Application

## 🚀 Project Overview
This **E-Commerce Web Application** is a fully functional online shopping platform built using the **MERN (MongoDB, Express, React, Node.js) stack**. It offers a seamless shopping experience with user authentication, product browsing, a shopping cart, payment integration, and an **Admin Dashboard** for order and inventory management.

## ✨ Features

### 🛒 **User Features:**
- User authentication (Login & Signup)
- Browse products with search and filtering options
- Add products to the cart
- Secure checkout with **Razorpay** payment gateway
- Order tracking and history
- Responsive UI for an optimal shopping experience

### 🔑 **Admin Dashboard:**
- **Product Management**: Add, update, and delete products
- **Order Management**: View and process customer orders
- **User Management**: View registered users
- **Dashboard Analytics**: Track sales, revenue, and inventory

## 🛠️ Tech Stack
- **Frontend**: React.js (with Redux for state management)
- **Backend**: Node.js & Express.js
- **Database**: MongoDB (with Mongoose ODM)
- **Authentication**: JWT (JSON Web Tokens)
- **Payment Gateway**: Razorpay
- **Deployment**: Vercel (Frontend) & Render/Heroku (Backend)

## 📂 Project Structure
```
Ecommerce-Project/
│── backend/       # Express.js server, API routes, database models
│── frontend/      # React.js app with pages, components, Redux setup
│── .env          # Environment variables
│── package.json  # Dependencies and scripts
│── README.md     # Project Documentation
```

## ⚡ Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-repo/ecommerce-project.git
cd ecommerce-project
```

### 2️⃣ Install Dependencies
#### Backend:
```bash
cd backend
npm install
```
#### Frontend:
```bash
cd frontend
npm install
```

### 3️⃣ Configure Environment Variables
Create a `.env` file in the **backend** directory and add:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
RAZORPAY_KEY=your_razorpay_key
```

### 4️⃣ Run the Project
#### Start Backend Server
```bash
cd backend
npm run dev
```
#### Start Frontend Server
```bash
cd frontend
npm start
```

## 🚀 Deployment
- Frontend: Deployed using **Vercel** or **Netlify**
- Backend: Hosted on **Render** or **Heroku**

## 📸 Screenshots
### 🏠 Home Page
![Home Page](https://via.placeholder.com/1200x600)

### 🔑 Login Page
![Login Page](https://via.placeholder.com/1200x600)

### 🛍️ Shopping Page
![Shopping Page](https://via.placeholder.com/1200x600)

### 📊 Admin Dashboard
![Admin Dashboard](https://via.placeholder.com/1200x600)



---
**Made with ❤️ using MERN Stack**

