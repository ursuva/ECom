# 🛒 E-Commerce Website

A feature-rich **E-Commerce Website** designed to deliver a seamless shopping experience for users while providing robust backend operations for administrators.

This project integrates modern technologies to ensure **scalability, performance, and security**.

---

# 🚀 Features

## 📦 MongoDB & Redis Integration

* **MongoDB** used as the primary database to store:

  * User data
  * Product catalogs
  * Orders
  * Coupons

* **Redis** integrated for:

  * Caching frequently accessed data
  * Improving performance
  * Reducing latency

---

## 💳 Stripe Payment Integration

* Secure payment processing with Stripe
* Supports:

  * Credit/Debit cards
  * Wallet payments
* Smooth checkout experience

---

## 🔐 Authentication System

* JWT Authentication
* Access Token & Refresh Token implementation
* Password hashing for security
* Secure user session handling

---

## 👤 User Features

* User Signup & Login
* Protected Routes
* Persistent Shopping Cart
* Coupon Code Support
* Secure Checkout

---

## 🛍 E-Commerce Functionalities

### 📦 Product & Category Management

* Add products
* Update products
* Delete products
* Organize categories dynamically

### 🛒 Shopping Cart

* Add/remove products
* Real-time cart updates
* Persistent cart synchronization

### 💰 Checkout System

* Stripe payment integration
* Order placement
* Payment verification
* Email notifications after successful payment

### 🎟 Coupon Code System

* Admin-defined discount coupons
* Coupon validation during checkout

---

## 🛠 Admin Dashboard

* Manage Products
* Manage Orders
* Manage Users
* Sales Monitoring
* Role-based Access Control

---

## 📊 Sales Analytics

* Revenue tracking
* Customer behavior insights
* Interactive graphs & charts

---

## 🎨 UI & Design

Built using:

* React
* Vite
* Tailwind CSS

Features:

* Responsive Design
* Mobile Friendly UI
* Modern User Experience

---

# 🛡 Security Features

* JWT-based Authentication
* Secure HTTPS Communication
* Password Hashing
* Data Sanitization
* Protection against XSS & Injection attacks

---

# ⚡ Performance Optimizations

## 🔄 Redis Caching

* Faster API responses
* Reduced database load

## 🔐 Data Protection

* Encryption of sensitive information
* Secure payment handling
* Backup-ready architecture

---

# 🛠 Tech Stack

| Category       | Technology                |
| -------------- | ------------------------- |
| Frontend       | React, Vite, Tailwind CSS |
| Backend        | Node.js, Express.js       |
| Database       | MongoDB                   |
| Caching        | Redis                     |
| Authentication | JWT                       |
| Payments       | Stripe API                |

---

# 📂 Project Structure

```bash
E-Commerce/
│
├── backend/
├── frontend/
├── README.md
└── package.json
```

---

# 🚀 Getting Started

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/ursuva/ECom.git
cd ECom
```

---

## 2️⃣ Create `.env` File

```env
PORT=5000

MONGO_URI=your_mongo_uri

UPSTASH_REDIS_URL=your_redis_url

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key

CLIENT_URL=http://localhost:5173

NODE_ENV=development
```

---

## 3️⃣ Install Dependencies

### Backend

```bash
cd backend
npm install
```

### Frontend

```bash
cd frontend
npm install
```

---

## 4️⃣ Run the Project

### Start Backend

```bash
cd backend
npm run dev
```

### Start Frontend

```bash
cd frontend
npm run dev
```

---

# 🌐 Deployment

## Frontend Deployment

* Vercel

## Backend Deployment

* Render
* Railway

---


# 🤝 Contributing

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
