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
git clone https://github.com/yourusername/prescripto-hms.git
cd prescripto-hms
```

### 2. Backend Setup
```bash

cd Backend
npm install
```
### Create a .env file inside the server directory:
```bash
env

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
STRIPE_SECRET_KEY=your_stripe_key
RAZORPAY_KEY_ID=your_razorpay_id
RAZORPAY_KEY_SECRET=your_razorpay_secret
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
