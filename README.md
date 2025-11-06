# 🗂️ Task Management Tool

**Developed for the 10Pearls Shine Program (.NET Internship)**  
A full-stack task management system that enables users to manage, assign, and track tasks efficiently with secure authentication, detailed logging, and code quality checks.

---

## ⚙️ Tech Stack

**Backend:** ASP.NET Core • Entity Framework Core • SQL Server  
**Frontend:** React.js (Vite + TypeScript)  
**Logging:** Serilog  
**Testing:** xUnit  
**Code Quality:** SonarQube  
**Version Control:** Git & GitHub  

---

## 🚀 Key Features

- 🔐 **User Authentication & Authorization** — Role-based access for Admin and User.  
- 📝 **Task Management** — Create, read, update, and delete (CRUD) tasks with priorities and due dates.  
- 🧾 **Application Logging (Serilog)** — Centralized logging for debugging and monitoring.  
- 🗃️ **Database & Data Access** — Managed using Entity Framework Core and SQL Server.  
- ⚡ **Exception Handling** — Structured error responses and middleware-based handling.  
- 🧪 **Unit Testing (xUnit)** — Ensures reliability and stability of API endpoints.  
- 🧹 **Code Quality (SonarQube)** — Continuous inspection for bugs, code smells, and vulnerabilities.  
- 💻 **React Frontend** — Clean, responsive UI powered by Vite and TypeScript.  

---

## 🧩 Project Structure
```bash
ShineProject/
│
├── Backend/                # ASP.NET Core Web API
│   ├── Controllers/
│   ├── Models/
│   ├── Data/
│   ├── Properties/
│   └── Program.cs
│
├── frontend/               # React + Vite + TypeScript
│   ├── src/
│   ├── public/
│   └── vite.config.ts
│
└── README.md
```

## Frontend Setup 

```bash

cd frontend
npm install
npm run dev

```

## Additional Information

API (dev): http://localhost:5146
Frontend (dev): http://localhost:5173


