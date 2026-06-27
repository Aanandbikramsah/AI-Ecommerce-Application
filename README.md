# AI-Powered-Ecommerce-Application

A full-stack AI-powered e-commerce platform built using the MERN stack (MongoDB, Express.js, React.js, Node.js), featuring secure authentication, real-time payments, and smart product recommendations.

## Features

- 🛍️ Modern, responsive e-commerce UI built with React.js
- 🔐 Google Authentication via Firebase/Google API for secure login
- 💳 Razorpay payment gateway integration for secure transactions
- 📦 Full admin dashboard for product, order, and user management
- 🛒 Add to cart, checkout, and order booking functionality
- 📊 Real-time stock updates synced across the platform
- 🤖 AI-powered product recommendations based on user behavior
- 📱 Fully responsive design for mobile and desktop
- 🚀 Deployed live on Render

## Tech Stack

**Frontend:** React.js, CSS  
**Backend:** Node.js, Express.js  
**Database:** MongoDB  
**Authentication:** Firebase / Google API  
**Payments:** Razorpay API  
**Deployment:** Render  

## Project Structure
AI-Ecommerce-Application/

├── frontend/    # Customer-facing React app

├── backend/     # Node.js + Express API server

└── admin/       # Admin dashboard for managing products, orders & users

## Getting Started

### Prerequisites
- Node.js installed
- MongoDB connection (local or Atlas)
- Firebase project for authentication
- Razorpay API keys

### Installation

1. Clone the repository
```bash
   git clone https://github.com/Aanandbikramsah/AI-Ecommerce-Application.git
   cd AI-Ecommerce-Application
```

2. Install dependencies for frontend, backend, and admin
```bash
   cd frontend
   npm install

   cd ../backend
   npm install

   cd ../admin
   npm install
```

3. Set up environment variables (create a `.env` file in the `backend` directory)
MONGO_URI=your_mongodb_connection_string

FIREBASE_API_KEY=your_firebase_key

RAZORPAY_KEY_ID=your_razorpay_key

RAZORPAY_KEY_SECRET=your_razorpay_secret

4. Run the application
```bash
   # Run backend
   cd backend
   npm start

   # Run frontend (in a new terminal)
   cd frontend
   npm start

   # Run admin dashboard (in a new terminal)
   cd admin
   npm start
```

## Live Demo


## Author

**Aanand Bikram Sah**  
[LinkedIn](https://linkedin.com/in/aanand-shah-451776302) | [GitHub](https://github.com/Aanandbikramsah)
