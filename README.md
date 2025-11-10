# Hybrid Application Tracking System (MERN)

A full MERN-based Application Tracking System where Applicants can apply for jobs and track their status, while Admins can manage job openings and update applications. Technical roles also support automatic status updates through a Bot Mimic.

## ✅ Features

### Applicant
- Register / Login
- View job openings
- Apply for technical or non-technical roles
- Track application status
- Add comments to applications

### Admin
- Login to admin dashboard
- Create and manage job openings
- View all applications
- Update application status and add comments

### Bot Mimic (Automation)
- Automatically updates status for technical job applications

## ✅ How to Download the Project

1. Open this GitHub repository
2. Click **Code → Download ZIP**
3. Extract the project to your system

## ✅ Requirements (Install these first)

- Node.js
- MongoDB Community Server

Make sure MongoDB service is running.

## Setup

# ✅ Step 1 — Run Backend (Server)
1. Ensure the backend is running
2. Copy or set the backend base URL in `.env` or pass via Vite env:
   - Create `.env` in project root:
     ```
     VITE_API_BASE=http://localhost:5000/api
     ```
3. Extract the Backend Folder
4. Install and run:

```
npm install
npm run dev
```

# ✅ Step 2 — Run Frontend
1. Open a new terminal
2. Go to the **frontend** folder
3. Extract the Frontend Folder
4. Install and run:
```
npm install
npm run dev
```

## ✅ Using the System

1. Start MongoDB
2. Start backend
3. Start frontend
4. Open browser → `http://localhost:5173`
5. Login or Register
6. Apply for jobs or manage applications

---

## Project structure
- `src/` - React source
  - `pages/` - route pages (Login, Dashboard, Applicant, Admin, BotMimic)
  - `components/` - shared components (Nav, ProtectedRoute)
  - `api.js` - Axios wrapper for backend endpoints

## ✅ Developer

👤 Lithish

