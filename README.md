# 💊 CureSync

A full-stack prescription management application with frontend, backend, and admin panel components.


## 🛠 Prerequisites

- [Node.js](https://nodejs.org/en/download/)
- VS Code (recommended)
- Internet Connection
- MongoDB Atlas Account
- [Cloudinary](https://cloudinary.com/) Account (for file storage)
- (Optional) [Stripe](https://dashboard.stripe.com/register) & [Razorpay](https://accounts.razorpay.com/auth/) Accounts

---

## 🚀 Project Setup

### 🔧 Backend Setup

1. Open project folder in **VS Code**.
2. Open integrated terminal:
   - Right-click on `backend` folder → “Open in Integrated Terminal”.
3. Run:
   ```bash
   npm install

	4.	Create a .env file in the backend/ directory with:

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

MONGODB_URI=your_mongodb_connection_string

Replace <password> in Mongo URI with your password (avoid using @ in passwords).
Do not add / at the end of the Mongo URI.

	5.	(Optional) Add these if using payments:

STRIPE_SECRET_KEY=your_stripe_secret
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_SECRET_KEY=your_secret


	6.	Run the backend server:

npm run server

🖥️ Frontend Setup
	1.	Right-click on frontend folder → “Open in Integrated Terminal”.
	2.	Install dependencies:

npm install


	3.	Start development server:

npm run dev


	4.	Open http://localhost:5173 in your browser.

🛡️ Admin Panel Setup
	1.	Right-click on admin folder → “Open in Integrated Terminal”.
	2.	Install dependencies:

npm install


	3.	Start development server:

npm run dev


	4.	Open http://localhost:5174 in your browser.
