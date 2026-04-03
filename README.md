# 🚀 Coworking Booking Platform

A complete coworking space booking solution with a modern frontend and robust backend API.

## 🔗 Live Demos

| Service | URL | Status |
|---------|-----|--------|
| **Frontend** | [https://ritesh-portfolio-2026.vercel.app/](https://ritesh-portfolio-2026.vercel.app/) | ✅ Live |
| **Backend API** | [https://co-working-backend.onrender.com](https://co-working-backend.onrender.com) | ✅ Live |

---

## 📸 Screenshots

### 🏠 Home Page
![Home Page](./images/home.png)

### 📅 Booking Page
![Booking Page](./images/booking.png)

### 📊 Dashboard
![Dashboard](./images/dashboard.png)

---

## 📱 Frontend

Modern UI for users to explore office spaces, book plans, and manage their bookings.

### ✨ Features

- 🔍 Browse coworking office spaces
- 📅 Book hourly, daily, or monthly plans
- 👤 User authentication (Login / Register / OTP)
- 💳 Checkout with promo codes
- 📄 View & download invoices
- 🧑‍💼 Admin dashboard (manage offices, bookings, promos)
- 📱 Fully responsive design

### ⚙️ Tech Stack (Frontend)

- **Framework**: Next.js (App Router)
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **State Management**: React Hooks
- **API Integration**: Axios

### 🚀 Frontend Deployment

Deployed on **Vercel** - [https://ritesh-officespace.vercel.app/](https://ritesh-officespace.vercel.app/)
---

## 🖥️ Backend API

RESTful API powering the coworking platform with authentication, booking management, and admin controls.

### ✨ API Features

- 🔐 JWT Authentication & OTP verification
- 👥 User management (Register, Login, Profile)
- 🏢 Office space CRUD operations
- 📅 Booking system (hourly/daily/monthly plans)
- 🎟️ Promo code management
- 📊 Admin dashboard endpoints
- 📑 Invoice generation

### ⚙️ Tech Stack (Backend)

- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB with Mongoose
- **Authentication**: JWT, bcrypt, OTP (Nodemailer)
- **Validation**: Joi
- **Security**: Helmet, CORS, Rate limiting

### 🚀 Backend Deployment

Deployed on **Render** - [https://co-working-backend.onrender.com](https://co-working-backend.onrender.com)

---

## 📦 Local Development

### Prerequisites

- Node.js (v18 or higher)
- MongoDB (local or Atlas)
- npm or yarn

### Frontend Setup

```bash
# Clone the repository
git clone https://github.com/ritesh637/coworking-frontend.git
cd coworking-frontend

# Install dependencies
npm install

# Create .env.local file
echo "NEXT_PUBLIC_API_URL=http://localhost:5000" > .env.local

# Run development server
npm run dev
