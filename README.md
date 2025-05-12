# 🏨 Hotel Booking App – Full-Stack Project

[![React](https://img.shields.io/badge/Frontend-React-61DAFB?style=flat-square&logo=react)](#)
[![Node.js](https://img.shields.io/badge/Backend-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)](#)
[![Express](https://img.shields.io/badge/API-Express.js-black?style=flat-square&logo=express)](#)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)](#)
[![Project](https://img.shields.io/badge/Final%20Project-Group%20Work-blueviolet?style=flat-square)](#)

A complete hotel booking platform built as a **final group project**, featuring a modern React frontend and an Express.js backend with MongoDB.

---

## 🌐 Live Demo

🔗 [View Live App](#) 

---

## 🧭 Project Structure

HOTEL-BOOKING-MERN/
├── backend/
│ ├── controllers/
│ ├── Data/
│ ├── middlewares/
│ ├── models/
│ ├── routes/
│ ├── utils/
│ ├── .env
│ └── server.js
│
├── frontend/
│ ├── public/
│ ├── src/
│ │ ├── assets/
│ │ ├── components/
│ │ ├── context/
│ │ ├── locales/
│ │ ├── pages/
│ │ ├── utils/
│ │ ├── App.jsx
│ │ ├── i18n.js
│ │ ├── index.css
│ │ └── main.jsx
│ ├── .env
│ ├── index.html
│ └── vite.config.js
│
├── README.md
└── package.json (root if monorepo, or separate per front/back)

---

## 🚀 Features

### 🌐 Frontend (React + Vite)
- Clean, responsive UI
- Dynamic room listings
- Booking workflow
- Context API for state management
- i18n internationalization support

### ⚙️ Backend (Node.js + Express + MongoDB)
- RESTful API for room, user, and booking management
- Middleware for auth and error handling
- Modular route structure
- Environment configuration with `.env`

---

## 🛠️ Tech Stack

| Frontend     | Backend       | Database | Other Tools         |
|--------------|---------------|----------|----------------------|
| React (Vite) | Node.js       | MongoDB  | Context API, i18n    |
| CSS / Tailwind | Express.js   | Mongoose | dotenv, ESLint       |

---

## 🧑‍💻 How to Run Locally

### 1. Clone the repo

```bash
git clone git@github.com:Mila-Amen/Hotel-Landing-page.git
cd HOTEL-BOOKING-MERN
2. Setup backend
bash
Copy
Edit
cd backend
npm install
cp .env.example .env
# Add MongoDB URI and PORT in .env
npm run dev
3. Setup frontend
bash
Copy
Edit
cd ../frontend
npm install
cp .env.example .env
# Configure VITE_API_URL if needed
npm run dev
This full-stack app was developed as a final group project by:

[[Me]](https://github.com/Mila-Amen)

[[Teammate 1]](https://github.com/khushnaveed)

[[Teammate 2]](https://github.com/ljurado72)

[[Teammate 3]](https://github.com/zahra-rafieirad)

[[Teammate 4]](https://github.com/shameem-oss)

📄 License
This project is for educational use only and not for commercial distribution.

📢 Contributions
Want to improve or build on top of this?
You're welcome to fork it and create a pull request!



