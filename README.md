# 🏥 Prescripto – Hospital Management System (MERN + Vite + Tailwind)

**Prescripto** is a full-stack hospital management system designed to simplify healthcare administration and improve communication between doctors, patients, and hospital staff. Built with the latest tech like React 18, Vite, TailwindCSS, and secured with JWT, this app supports appointment scheduling, patient record management, file uploads, and integrated payments with Stripe and Razorpay.

---

## 🚀 Features

- 🔐 Secure User Authentication (JWT + bcrypt)
- 👩‍⚕️ Role-based access (Admin / Doctor / Patient)
- 📅 Appointment scheduling and tracking
- 📂 Patient health records and reports
- 📤 Cloudinary integration for file uploads
- 💳 Payments via Stripe and Razorpay
- 🗃️ Real-time notifications (via Toasts)
- 🌐 Fully responsive UI with Tailwind CSS

---

## 🛠️ Tech Stack

### Frontend:
- React 18 (`react`, `react-dom`)
- Vite (for blazing-fast build)
- Tailwind CSS
- React Router DOM (v6)
- Axios (for API calls)
- React Toastify (alerts/notifications)

### Backend:
- Node.js + Express.js
- MongoDB + Mongoose
- JSON Web Tokens (`jsonwebtoken`)
- bcrypt (password hashing)
- Cloudinary (file hosting)
- Multer (file uploads)
- Stripe + Razorpay (payment integration)
- dotenv, cors, validator

---

## 📦 Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/ayushsingh991399/HospitalManagmentSystem
cd HospitalManagmentSystem
```

### 2. Backend Setup
```bash

cd Backend
npm install
```
### Create a .env file inside the server directory:
```bash
env
CURRENCY = "INR"
JWT_SECRET="AyushSingh"

# Admin Panel Credentials
ADMIN_EMAIL = "admin@example.com"
ADMIN_PASSWORD = "Ayush12345"

# MongoDB Setup ( required )
MONGODB_URI = "------ MongoDB Secret Key here ------"

# Cloudinary Setup ( required )
CLOUDINARY_NAME = '------ Cloudinary Secret Key here ------'
CLOUDINARY_API_KEY = '------ Cloudinary Secret Key here ------'
CLOUDINARY_SECRET_KEY = '------ Cloudinary Secret Key here ------'

# Razorpay Payment Integration
RAZORPAY_KEY_ID = "------ Razorpay Key Id here ------"
RAZORPAY_KEY_SECRET = "------ Razorpay Key Secret here ------"

# Stripe Payment Integration
STRIPE_SECRET_KEY="------ Stripe Secret Key here ------"

```
###Start the backend:
```bash
npm run dev
```
### 3. Frontend Setup
```bash

cd Admin
cd Frontend
npm install
npm run dev
```
