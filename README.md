MERN Authentication Dashboard

A full-stack MERN authentication and task management dashboard built with a strong focus on security, scalability, and clean architecture.
This project demonstrates real-world frontend–backend integration using JWT authentication, protected routes, and a modern responsive UI.

📌 Project Overview

The application allows users to:

Register and log in securely

Access a protected dashboard

Manage tasks with full CRUD operations

Search and filter tasks

Log out securely

The backend exposes secure APIs, and the frontend consumes them using token-based authentication.

🚀 Features
Authentication

User registration and login

JWT-based authentication

Password hashing using bcrypt

Protected frontend and backend routes

Dashboard

Display logged-in user profile

Create, read, update, delete tasks

Mark tasks as completed

Search and filter tasks

Logout functionality

Security

Hashed passwords (bcrypt)

JWT verification middleware

Authorization required for protected APIs

Centralized error handling

Scalability

Modular backend architecture

Separation of concerns (routes, controllers, models, middleware)

Easy to extend with roles, pagination, or additional entities

🛠 Tech Stack
Frontend

React (Vite)

Tailwind CSS

React Router DOM

Backend

Node.js

Express.js

MongoDB with Mongoose

JWT (JSON Web Tokens)

bcryptjs

Tools

MongoDB Atlas

Postman

Git & GitHub

📂 Project Structure
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