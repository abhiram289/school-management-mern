#  School Management System
A complete **MERN-based School Management System** featuring student/teacher dashboards, attendance tracking, notices, authentication, and more — built for smooth school administration.

##  Project Preview

| Login Page | Home Page |
|----------|------------|
| ![Login Screenshot](/images/login.png) | ![Home Screenshot](/images/home.png) |

| Dashboard | Attendance |
|----------|------------|
| ![Dashboard Screenshot](/images/dashboard.png) | ![Attendance Screenshot](/images/attendance.png) |

##  Tech Stack

### **Frontend**
- React.js  
- React Router  
- Axios  
- CSS Modules  
- ProtectedRoute wrapper  
- Responsive design  

### **Backend**
- Node.js  
- Express.js  
- MongoDB + Mongoose  
- REST API architecture  

### **Database**
- MongoDB Atlas / Local MongoDB

##  Folder Structure

```
School-Management-System-MERN/
│
├── backend/
│   ├── config/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   ├── .env.example
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── pages/
│   │   ├── utils/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
├── images/
│   └── screenshots used in README
│
├── .gitignore
└── README.md
```

##  Installation & Setup

### **1️⃣ Clone the repository**
```
git clone https://github.com/abhiram289/School-Management-System-MERN.git
cd School-Management-System-MERN

```

## **2️⃣ Backend Setup**

```
cd backend
npm install
```

Create a `.env` file:

```
MONGO_URL=your_mongodb_connection_string
PORT=5000
```

Run backend:
```
npm start
```

Backend runs at: **http://localhost:5000**

## **3️⃣ Frontend Setup**

```
cd frontend
npm install
npm start
```

Frontend runs at: **http://localhost:3000**

##  Features

### 👨🏻‍💼 **Admin**
- Manage students & teachers  
- View all attendance  
- Add and manage notices  
- Dashboard analytics  

### 🧑‍🏫 **Teacher**
- Mark attendance  
- Manage student records  
- View assigned classes  

### 🧑‍🎓 **Student**
- View attendance  
- View notices  
- Access student dashboard  

### 🔐 **Security**
- Protected routes  
- Role-based access  

##  More Screenshots

### About Page  
![About](/images/about.png)

### Notices  
![Notices](/images/notices.png)

### Students Management  
![Students](/images/students.png)

## 🛑 Environment Variables

Backend `.env` example:

```
MONGO_URL=
PORT=5000
JWT_SECRET=yourSecret (if using auth)
```

## 🚧 Deployment Status

This project is currently intended for **local development**.

- Frontend and backend run locally
- Backend is not deployed to a public server
- UI screenshots are provided for demonstration

## Author

[abhiram289](https://github.com/abhiram289/)

