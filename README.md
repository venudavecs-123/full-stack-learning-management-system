# Full-Stack Learning Management System

A production-ready Learning Management System (LMS) prototype with complete authentication, CRUD operations, and a responsive UI. Built as a monorepo with both frontend (Next.js) and backend (Node.js/Express) codebases.

## Features

- Modern, responsive UI (Next.js + React)
- User authentication and session management
- Full CRUD for courses, modules, assignments, and users
- RESTful API backend with MongoDB
- Scalable, modular architecture
- State management with Redux Toolkit
- Clean separation of frontend and backend code

## Monorepo Structure

```
full-stack-learning-management-system/
├── frontend/   # Next.js + React client
└── backend/    # Node.js + Express server
```

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm or yarn
- MongoDB (local or cloud)

### Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/venudavecs-123/full-stack-learning-management-system.git
   cd full-stack-learning-management-system
   ```

2. **Install dependencies:**

   - Frontend:
     ```bash
     cd frontend
     npm install
     # or
     yarn
     ```

   - Backend:
     ```bash
     cd ../backend
     npm install
     # or
     yarn
     ```

3. **Configure environment variables:**
   - Create `.env` files in both `frontend` and `backend` as needed (see `.env.example` if provided).

4. **Run the applications:**

   - Backend:
     ```bash
     cd backend
     npm start
     # or
     yarn start
     ```

   - Frontend (in a new terminal):
     ```bash
     cd frontend
     npm run dev
     # or
     yarn dev
     ```

5. **Access the app:**
   - Frontend: [http://localhost:3000](http://localhost:3000)
   - Backend API: [http://localhost:5000](http://localhost:5000) (or as configured)

## Tech Stack

- **Frontend:** Next.js, React, Redux Toolkit, Tailwind CSS
- **Backend:** Node.js, Express.js, MongoDB, Mongoose
- **Other:** JWT Auth, REST API, Modular Architecture

## Screenshots

_Add screenshots or GIFs here to showcase the UI and features._

## License

This project is licensed under the MIT License.
