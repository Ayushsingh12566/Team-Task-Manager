# 🚀 Team Task Manager

A modern full-stack Team Task Manager built with Next.js, MongoDB, NextAuth, and TypeScript.  
Manage teams, projects, and tasks with secure authentication and role-based access.

---

## ✨ Features

- 🔐 Secure Authentication
- 👥 Admin & Member Roles
- 📁 Team & Project Management
- ✅ Task Assignment & Tracking
- 📅 Due Date Support
- 📊 Dashboard Analytics
- 🌙 Dark / Light Mode
- 📧 Forgot & Reset Password
- ⚡ Responsive Modern UI

---

# 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| Next.js | Full Stack Framework |
| TypeScript | Type Safety |
| MongoDB | Database |
| Mongoose | ODM |
| NextAuth | Authentication |
| Tailwind CSS | Styling |
| Zod | Validation |
| React Hot Toast | Notifications |

---

# 🔐 Authentication

- User Signup & Login
- Password Hashing with bcrypt
- Forgot Password Flow
- Reset Password via Email

---

# 👥 User Roles

## Admin
- Create Projects
- Assign Tasks
- Manage Teams
- Track Progress

## Member
- View Assigned Tasks
- Update Task Status
- Monitor Work Progress

---

# 📂 Folder Structure

```bash
src/
├── app/
├── api/
├── components/
├── models/
├── lib/
├── hooks/
└── auth.ts
```

---

# ⚙️ Environment Variables

Create `.env.local` file:

```env
MONGODB_URI=

NEXTAUTH_SECRET=
NEXTAUTH_URL=http://localhost:3000

APP_URL=http://localhost:3000

SMTP_HOST=smtp.gmail.com
SMTP_PORT=465
SMTP_USER=your_email@gmail.com
SMTP_PASS=your_app_password
SMTP_FROM="Team Task Manager <your_email@gmail.com>"
```

---

# ▶️ Run Locally

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm run dev
```

Production build:

```bash
npm run build
npm run start
```

---

# 🌐 API Routes

## Auth APIs

```bash
POST /api/auth/register
POST /api/auth/forgot-password
POST /api/auth/reset-password
```

## Team APIs

```bash
GET /api/teams
POST /api/teams
POST /api/teams/:teamId/join
```

## Project APIs

```bash
GET /api/projects
POST /api/projects
```

## Task APIs

```bash
GET /api/tasks
POST /api/tasks
PATCH /api/tasks/:taskId/status
```

---

# 📊 Dashboard Features

- Total Tasks Overview
- Pending & Completed Tasks
- Overdue Task Highlighting
- Project Progress Tracking

---

# 📸 Screenshots

## Admin Panel
- Admin Login
- Dashboard
- Project Management
- Task Management

## Member Panel
- Member Login
- Dashboard
- Assigned Tasks
- Project Access

---

# 🚀 Local Access

```bash
http://localhost:3000
```

Health Check:

```bash
http://localhost:3000/api/health
```

---

# 👨‍💻 Developer

## Ayush Singh

---

# 📄 License

This project is made for learning and portfolio purposes.
