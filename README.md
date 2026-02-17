# Secure Auth RBAC Fullstack Application

A scalable REST API with JWT Authentication, Role-Based Access Control (RBAC), and CRUD functionality, along with a basic frontend interface to interact with the APIs.

---

## 🚀 Tech Stack

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Bcrypt (Password Hashing)

### Frontend
- React.js
- Axios
- Protected Routes using JWT

---

## 🔐 Features Implemented

### Authentication
- User Registration
- User Login
- Password Hashing using bcrypt
- JWT Token Generation & Verification

### Role-Based Access Control (RBAC)
- User role
- Admin role
- Protected routes based on role

### CRUD Operations
- Create, Read, Update, Delete for secondary entity (Tasks)
- Proper HTTP status codes
- Centralized error handling

### Security
- Secure JWT handling
- Input validation
- Protected API routes
- Environment variable protection

---

## 📂 Project Structure

auth-crud-api/
│
├── backend/
│   ├── config/
│   │   ├── db.js
│   │   └── token.js
│   │
│   ├── controllers/
│   │   └── auth.controller.js
│   │
│   ├── model/
│   │   └── user.model.js
│   │
│   ├── routes/
│   │   └── auth.route.js
│   │
│   ├── .env
│   ├── index.js
│   ├── package.json
│   └── package-lock.json
│
├── frontend/
│   ├── public/
│   ├── node_modules/
│   │
│   └── src/
│       ├── assets/
│       │
│       ├── Component/
│       │   └── Nav.jsx
│       │
│       ├── Context/
│       │   └── AuthContext.jsx
│       │
│       ├── pages/
│       │   ├── Home.jsx
│       │   ├── Login.jsx
│       │   └── SignUp.jsx
│       │
│       ├── App.jsx
│       ├── App.css
│       ├── index.css
│       └── main.jsx
│
├── .gitignore
└── README.md



