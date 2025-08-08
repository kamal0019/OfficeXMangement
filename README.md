# 🏢 OfficeXManagement

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

> **OfficeXManagement** is a modern, secure, and scalable Office Management System built with **Node.js, Express, MongoDB, and TypeScript**.  
> It streamlines office operations such as employee management, attendance tracking, and role-based access control.

---

## 🚀 Features

- 🔐 **JWT Authentication** – Secure login and protected routes
- 👥 **Role-Based Access** – Admin, HR, and Employee dashboards
- 📋 **Employee Management** – Add, edit, delete employees
- 📅 **Attendance Tracking** – Mark and view attendance records
- ⚡ **REST API** – Ready for frontend integration
- 🛡 **Security** – Input validation & password hashing

---

## 📂 Project Structure

```
OfficeXManagement/
├── server/              # Backend code
│   ├── src/
│   │   ├── controllers/ # Route logic
│   │   ├── models/      # Mongoose schemas
│   │   ├── routes/      # API endpoints
│   │   ├── middlewares/ # Auth & error handling
│   │   └── utils/       # Helper functions
├── client/              # (Planned) Frontend code
├── package.json
└── README.md
```

---

## 🛠 Tech Stack

**Backend:**
- Node.js
- Express.js
- TypeScript
- MongoDB + Mongoose
- JWT + bcrypt

**Frontend (Coming Soon):**
- React + TypeScript
- Tailwind CSS
- Axios

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/kamal0019/OfficeXMangement.git
cd OfficeXMangement
```

### 2️⃣ Install dependencies
**For Backend:**
```bash
cd server
npm install
```

**For Frontend (coming soon):**
```bash
cd client
npm install
```

### 3️⃣ Environment variables
Create a `.env` file in `server/` and add:
```
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
```

### 4️⃣ Run the backend server
```bash
npm run dev
```
Server will start on `http://localhost:5000`.

---

## 📌 API Endpoints

| Method | Endpoint           | Description           | Auth Required |
|--------|-------------------|-----------------------|--------------|
| POST   | `/api/auth/login` | User login            | ❌ No         |
| POST   | `/api/auth/register` | Register new user | ❌ No         |
| GET    | `/api/employees`  | Get all employees     | ✅ Yes        |
| POST   | `/api/employees`  | Add new employee      | ✅ Yes        |
| PUT    | `/api/employees/:id` | Update employee   | ✅ Yes        |
| DELETE | `/api/employees/:id` | Delete employee   | ✅ Yes        |

---

## 🤝 Contributing

1. Fork the repo
2. Create a new branch:  
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes & commit:  
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to branch & create PR

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 💌 Contact
**Author:** [Kamal Prajapat](https://github.com/kamal0019)  
📧 Email: kamal@example.com  
💼 LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/your-profile)

---
