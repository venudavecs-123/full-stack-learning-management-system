# Kambaz Full Stack Learning Management System

---

## Repository

[https://github.com/venudavecs-123/full-stack-learning-management-system](https://github.com/venudavecs-123/full-stack-learning-management-system)

A monorepo for a modern Learning Management System (LMS) with a Next.js (React/TypeScript) frontend and an Express.js backend. This project supports user authentication, course management, assignments, modules, grades, and more.

---

## Project Structure

```
full-stack-learning-management-system/
├── backend/           # Node.js Express REST API
│   ├── Kambaz/        # Main backend modules
│   │   ├── Assignments/
│   │   ├── Courses/
│   │   ├── Database/
│   │   ├── Enrollments/
│   │   ├── Modules/
│   │   └── Users/
│   ├── Hello.js
│   ├── index.js
│   └── package.json
├── frontend/          # Next.js (React/TypeScript) web app
│   ├── app/
│   │   └── (Kambaz)/  # Main app routes (Account, Courses, Dashboard, etc.)
│   ├── public/
│   ├── package.json
│   └── ...
└── README.md          # Project documentation (this file)
```

---

## Backend

- **Framework:** Node.js, Express.js
- **Location:** `backend/`
- **Features:**
  - RESTful API for users, courses, assignments, modules, enrollments, grades
  - Modular DAO and route structure for each resource
  - Session management, CORS, and environment configuration

### Backend Directory Structure
- `Kambaz/Assignments/` — Assignment routes and data access
- `Kambaz/Courses/` — Course routes and data access
- `Kambaz/Database/` — Database models (assignments, courses, enrollments, modules, users)
- `Kambaz/Enrollments/` — Enrollment routes and data access
- `Kambaz/Modules/` — Module routes and data access
- `Kambaz/Users/` — User routes and data access

### Running the Backend

```bash
cd backend
npm install
npm start
```

The backend server will start (default: http://localhost:4000 or as configured in `index.js`).

---

## Frontend

- **Framework:** Next.js (React, TypeScript)
- **Location:** `frontend/`
- **Features:**
  - Modern UI for LMS features: dashboard, courses, assignments, grades, modules, calendar, inbox, etc.
  - Route-based structure for each major feature
  - Account management (profile, sign in, sign up)

### Frontend Directory Structure
- `app/(Kambaz)/` — Main LMS app routes (Account, Courses, Dashboard, etc.)
- `app/(Kambaz)/Courses/[cid]/` — Dynamic course pages (Assignments, Grades, Home, Modules, etc.)
- `public/` — Static assets and images

### Running the Frontend

```bash
cd frontend
npm install
npm run dev
```

The frontend will be available at [http://localhost:3000](http://localhost:3000).

---

## Development Notes
- The frontend and backend are decoupled; update API endpoints in the frontend as needed to match backend routes.
- Environment variables can be set in `.env` files for both frontend and backend as required.
- No Labs or demo code is present; the codebase is focused on core LMS features.

---

## License

MIT License. See individual files for copyright.
