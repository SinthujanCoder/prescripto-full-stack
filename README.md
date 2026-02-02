# Hospital Management System (MERN Stack)

## 📌 Overview

This is a **full‑stack Hospital Management System** built using the **MERN stack (MongoDB, Express, React, Node.js)**. The system helps manage hospital operations such as patient appointments, doctors, prescriptions, and administrative controls through separate user and admin applications.

🔗 **Live Preview (User):** [https://prescripto-ochre.vercel.app/](https://prescripto-ochre.vercel.app/)

🔗 **Live Preview (Admin):** [https://prescripto-admin-xi-lovat.vercel.app/](https://prescripto-admin-xi-lovat.vercel.app/)

---

## 📚 Table of Contents

* Features
* Technologies Used
* Installation & Setup
* Running the Project
* Environment Variables
* Live Demo
* Support & Contact

---

## ✨ Features

* User authentication and authorization
* Patient appointment booking
* Doctor management
* Prescription management
* Admin dashboard for hospital operations
* Image/file upload support (Cloudinary)
* Secure payment integration (Stripe / Razorpay – optional)
* Responsive UI

---

## 🛠 Technologies Used

* **Frontend:** React.js, Vite, Context API
* **Backend:** Node.js, Express.js
* **Database:** MongoDB Atlas
* **Authentication:** JWT
* **File Storage:** Cloudinary
* **Payments (Optional):** Stripe, Razorpay
* **Styling:** CSS

---

## ⚙️ Installation & Setup Guide

### 🎥 Video Tutorial

**How to Setup & Run This Project (Video Tutorial):**
👉 *Click here* (add video link)

---

### Install Node.js (Skip if already installed)

1. Visit [https://nodejs.org/en/download/](https://nodejs.org/en/download/)
2. Download and install Node.js
3. Follow the installer instructions

> Recommended: Node.js v20+

---

## 🚀 Running Order (Important)

➡️ **Always run the Backend first**, then start the Frontend and Admin panel.

---

## 🔧 Backend Setup

1. Open the project folder in **VS Code**
2. Right‑click on the `backend` folder → **Open in Integrated Terminal**
3. Install dependencies:

```sh
npm install
```

---

### 🔐 Environment Variables (`backend/.env`)

#### Cloudinary Setup (Required)

1. Create an account at [https://cloudinary.com/](https://cloudinary.com/)
2. Go to Dashboard and copy:

   * Cloud Name
   * API Key
   * API Secret

```env
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

---

#### MongoDB Setup

1. Sign up at MongoDB Atlas
2. Create a new project
3. Build a database (M0 – Free Tier)
4. Create a database user

   * ⚠️ Do NOT use `@` in the password
5. Whitelist IP address: `0.0.0.0/0`
6. Click **Connect → Compass**
7. Copy the connection string
8. Paste it into `.env` and replace `<password>`

```env
MONGODB_URI=your_mongodb_connection_string
```

> ⚠️ Do not add `/` at the end of the MongoDB URI

---

#### Stripe Setup (Optional)

```env
STRIPE_SECRET_KEY=your_stripe_secret_key
```

---

#### Razorpay Setup (Optional)

```env
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_SECRET_KEY=your_secret_key
```

---

### ▶️ Run Backend Server

```sh
npm run server
```

✅ Keep backend running before starting frontend or admin.

---

## 🌐 Frontend Setup

1. Right‑click on `frontend` → **Open in Integrated Terminal**
2. Install dependencies:

```sh
npm install
```

3. Start frontend:

```sh
npm run dev
```

4. Open in browser:

```
http://localhost:5173
```

---

## 🧑‍💼 Admin Panel Setup

1. Right‑click on `admin` → **Open in Integrated Terminal**
2. Install dependencies:

```sh
npm install
```

3. Start admin panel:

```sh
npm run dev
```

4. Open in browser:

```
http://localhost:5174
```

---

## 🌍 Live Demo

* **User App:** [https://prescripto-ochre.vercel.app/](https://prescripto-ochre.vercel.app/)
* **Admin App:** [https://prescripto-admin-xi-lovat.vercel.app/](https://prescripto-admin-xi-lovat.vercel.app/)

---

## 📞 Support & Contact

If you face any issues or have questions:

* Instagram: [https://instagram.com/sinthujan_dev](https://instagram.com/sinthujan_dev)
* GitHub: [https://github.com/SinthujanCoder](https://github.com/SinthujanCoder)

---

Happy Coding! 🏥💻
