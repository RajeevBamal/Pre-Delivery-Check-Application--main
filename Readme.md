# 🚗 PDC Pro Delivery Check Application

A modern **Full-Stack Vehicle Pre-Delivery Inspection Application** built using **React, TypeScript, Node.js, Express, MongoDB, and Cloudinary**. This application streamlines the vehicle delivery inspection process by enabling users to perform detailed inspections, upload vehicle images, generate PDF reports, and manage inspection records through a responsive dashboard.

---

## 🌐 Live Demo

### 🚀 Frontend
**Netlify:** https://pre-delivery-check-web-app.netlify.app

### ⚙️ Backend API
**Render:** https://pre-delivery-check-application.onrender.com

---

## 📸 Preview

> Add screenshots of your application inside a `screenshots` folder and update the paths below.

| Login | Dashboard |
|--------|-----------|
| ![](screenshots/login.png) | ![](screenshots/dashboard.png) |

| Inspection Form | PDF Report |
|-----------------|------------|
| ![](screenshots/inspection.png) | ![](screenshots/report.png) |

---

# ✨ Features

- 🔐 Secure User Authentication (JWT)
- 👤 User Registration & Login
- 🚘 Step-by-Step Vehicle Inspection
- 📷 Upload Vehicle Images using Cloudinary
- 📄 Generate PDF Inspection Reports
- 📊 Dashboard for Managing Inspections
- 🔍 View Inspection History
- 📱 Fully Responsive UI
- ⚡ Fast Performance with Vite
- 🎨 Modern UI using Tailwind CSS

---

# 🛠 Tech Stack

## Frontend

- React.js
- TypeScript
- Vite
- Tailwind CSS
- React Router

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

## Cloud Services

- Cloudinary

---

# 📂 Project Structure

```text
PDC-Pro-Delivery-Check-Application/
│
├── backend/
│   ├── config/
│   │   ├── db.js
│   │   └── cloudinary.js
│   │
│   ├── middleware/
│   │   └── authMiddleware.js
│   │
│   ├── models/
│   │   ├── User.js
│   │   └── Inspection.js
│   │
│   ├── routes/
│   │   ├── authRoutes.js
│   │   └── inspectionRoutes.js
│   │
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── contexts/
│   │   ├── pages/
│   │   ├── utils/
│   │   ├── App.tsx
│   │   └── index.css
│   │
│   ├── public/
│   ├── index.html
│   ├── vite.config.ts
│   └── package.json
│
└── README.md
```

---

# 🚀 Getting Started

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/PDC-Pro-Delivery-Check-Application.git

cd PDC-Pro-Delivery-Check-Application
```

---

# ⚙️ Backend Setup

```bash
cd backend

npm install

npm start
```

### Create `.env`

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloud_name

CLOUDINARY_API_KEY=your_api_key

CLOUDINARY_API_SECRET=your_api_secret
```

---

# 💻 Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

---

# 🌍 Local URLs

| Service | URL |
|---------|------|
| Frontend | http://localhost:5173 |
| Backend | http://localhost:5000 |

---

# 🔐 Authentication

- User Registration
- User Login
- JWT Authentication
- Protected Routes

---

# 🚘 Inspection Workflow

1. Vehicle Information
2. Exterior Inspection
3. Interior Inspection
4. Accessories Inspection
5. Upload Vehicle Images
6. Review Details
7. Generate PDF Report

---

# ☁️ Cloudinary Integration

Vehicle images are uploaded securely to **Cloudinary**, providing reliable cloud storage and optimized image delivery.

---

# 📄 REST API

## Authentication

```http
POST /api/auth/register
POST /api/auth/login
```

## Inspection

```http
GET    /api/inspections
POST   /api/inspections
GET    /api/inspections/:id
PUT    /api/inspections/:id
DELETE /api/inspections/:id
```

---

# 📷 Screenshots

```
screenshots/
│── login.png
│── dashboard.png
│── inspection.png
│── report.png
```

---

# 🚀 Deployment

## Frontend (Netlify)

https://pre-delivery-check-web-app.netlify.app

## Backend (Render)

https://pre-delivery-check-application.onrender.com

---

# 🔮 Future Improvements

- ✅ Admin Dashboard
- ✅ Role-Based Authentication
- ✅ Email PDF Reports
- ✅ Search & Filter Inspections
- ✅ Vehicle History Tracking
- ✅ Dark Mode
- ✅ Notifications
- ✅ Offline Support (PWA)

---

# 🤝 Contributing

Contributions are welcome!

1. Fork this repository

2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Create a Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Developer

**Rajeev Bamal**

🌐 **Portfolio Project**

Frontend: https://pre-delivery-check-web-app.netlify.app

Backend API: https://pre-delivery-check-application.onrender.com

GitHub: https://github.com/your-github-username

---

## ⭐ Show Your Support

If you found this project helpful, please give it a **⭐ Star** on GitHub.

It motivates me to build more open-source projects.

---

### Made with ❤️ by Rajeev Bamal
