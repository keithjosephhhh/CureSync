# 💊 CureSync - Full Stack Prescription Management System

CureSync is a modern, full-stack prescription management system designed to streamline medical workflows for patients, doctors, and administrators. With seamless cloud storage, payment integration, and separate admin access, CureSync delivers a complete digital healthcare solution.

---

## 🔧 Tech Stack

- **Frontend**: React (Vite)
- **Backend**: Node.js, Express
- **Database**: MongoDB Atlas
- **File Storage**: Cloudinary
- **Payments**: Stripe & Razorpay (Optional)
- **Environment**: VS Code, Node.js

---

## 🚀 Features

- 🩺 Prescription upload and viewing
- 👩‍⚕️ Doctor-patient interaction interface
- 💳 Secure online payments via Stripe/Razorpay
- 🗂️ Admin dashboard to manage users and data
- ☁️ Cloud-based file storage for prescriptions and reports

---

## 🛠️ Prerequisites

- [Node.js](https://nodejs.org/en/download/)
- [MongoDB Atlas Account](https://www.mongodb.com/cloud/atlas/register)
- [Cloudinary Account](https://cloudinary.com/)
- (Optional) [Stripe](https://dashboard.stripe.com/register) & [Razorpay](https://accounts.razorpay.com/auth/) accounts

---

## ⚙️ Setup Instructions

### 🔙 Backend Setup

1. Open project folder in **VS Code**.
2. Open terminal in the `backend` folder:
   ```bash
   cd backend
   npm install

	3.	Create a .env file inside backend/ with the following:

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

MONGODB_URI=your_mongodb_connection_string

STRIPE_SECRET_KEY=your_stripe_secret        # Optional
RAZORPAY_KEY_ID=your_key_id                 # Optional
RAZORPAY_SECRET_KEY=your_secret             # Optional

	Note: Replace <password> in Mongo URI with your actual password. Avoid using @ in the password. Do not add / at the end of the URI.

	4.	Start the backend server:

npm run server

🖼️ Frontend Setup
	1.	Open terminal in the frontend folder:

cd frontend
npm install
npm run dev


	2.	Visit: http://localhost:5173

🛡️ Admin Panel Setup
	1.	Open terminal in the admin folder:

cd admin
npm install
npm run dev


	2.	Visit: http://localhost:5174

