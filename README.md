# Tumkur City Transit Project

This project consists of a Node.js/Express backend and a React/Vite frontend.

## Prerequisites

- Node.js installed on your machine.
- PostgreSQL installed and running (for the backend).

## Setup Instructions

### Backend

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up your `.env` file (environment variables for DB connection).
4. Run the database schema script (`src/schema.sql`) in your PostgreSQL database.
5. Start the server:
   ```bash
   npm run dev
   ```

### Frontend

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open http://localhost:5173 to view the website.

## Admin Features

Access the admin panel at `/admin` to manage content, blogs, and users.
