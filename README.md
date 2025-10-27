# Hybrid ATS - Frontend

This is a Vite + React frontend for the Hybrid Application Tracking System. It integrates with the provided backend (MERN).

## Features implemented
- Role-based login (Applicant, Admin, Bot Mimic)
- Dashboards with charts (react-chartjs-2 + chart.js)
- Applicant flow: create applications, add comments
- Admin flow: create jobs, manage non-technical applications, change status & add comments
- Bot Mimic: trigger automated updates for technical roles
- JWT token stored in localStorage for API auth

## Setup

1. Ensure the backend is running (the backend you uploaded should listen on port 5000 by default).
2. Copy or set the backend base URL in `.env` or pass via Vite env:
   - Create `.env` in project root:
     ```
     VITE_API_BASE=http://localhost:5000/api
     ```
3. Install and run:
```
npm install
npm run dev
```

## Project structure
- `src/` - React source
  - `pages/` - route pages (Login, Dashboard, Applicant, Admin, BotMimic)
  - `components/` - shared components (Nav, ProtectedRoute)
  - `api.js` - Axios wrapper for backend endpoints

## Notes & Next steps
- This is a minimal, modular frontend scaffold. You can extend forms, validation, and UI styling (Tailwind, Chakra or Material UI).
- Add Postman collection (export) or connect Swagger link from backend.
- Sample credentials should be created in the backend. Use the backend's seed or register endpoints.

