# MERN Authentication Dashboard

A full-stack **MERN Authentication and Task Management Dashboard** built with a focus on **security, scalability, and clean architecture**.  
This project demonstrates real-world **JWT-based authentication**, **protected routes**, and **frontend–backend integration**.

---

## Features

### Authentication
- User registration and login
- JWT-based authentication
- Password hashing using bcrypt
- Protected frontend and backend routes

### Dashboard & Tasks
- Display logged-in user profile
- Create, read, update, delete tasks (CRUD)
- Mark tasks as completed
- Search and filter tasks
- Secure logout

### Security & Scalability
- Hashed passwords (bcrypt)
- JWT verification middleware
- Authorization required for protected APIs
- Centralized error handling
- Modular backend architecture

---

## Tech Stack

- **Frontend:** React (Vite), Tailwind CSS, React Router DOM
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose, MongoDB Atlas)
- **Authentication:** JWT, bcryptjs
- **Tools:** Postman, Git & GitHub

---

## Project Structure

```bash
mern-auth-dashboard/
│
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   │   ├── LoginPage.jsx
│   │   │   ├── RegisterPage.jsx
│   │   │   └── Dashboard.jsx
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
├── backend/
│   ├── src/
│   │   ├── config/
│   │   │   └── db.js
│   │   ├── controllers/
│   │   ├── routes/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── app.js
│   │   └── server.js
│   └── package.json
│
└── README.md


⚙️ Environment Variables

Create a .env file inside the backend directory:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

▶️ Run the Project Locally
1️⃣ Clone the repository
git clone https://github.com/your-username/mern-auth-dashboard.git
cd mern-auth-dashboard

2️⃣ Start Backend
cd backend
npm install
npm run dev


Backend runs at:

http://localhost:5000

3️⃣ Start Frontend
cd frontend
npm install
npm run dev


Frontend runs at:

http://localhost:5173