# Full-Stack To-Do List Web App

This project is a simple full-stack to-do list web app with CRUD functionality. It includes both frontend (Next.js) and backend (Node.js + Express with Prisma ORM) components. The backend uses PostgreSQL as the database, and the frontend is styled using Tailwind CSS with ShadCN for UI components.

## Table of Contents
1. [Tech Stack](#tech-stack)
2. [Installation](#installation)
3. [Running Locally](#running-locally)
   - [Backend Setup](#backend-setup)
   - [Frontend Setup](#frontend-setup)
4. [API Endpoints](#api-endpoints)
5. [Database Schema](#database-schema)
6. [Approach](#approach)
7. [Future Improvements](#future-improvements)
8. [License](#license)


## Tech Stack

### Frontend:
- **Next.js**
- **Tailwind CSS**
- **ShadCN UI**
- **React Query** for data fetching

### Backend:
- **Node.js** with Express
- **Prisma ORM**
- **PostgreSQL** for task management
- **Cors** for cross-origin requests
- **Docker** (Optional for running PostgreSQL)

---

## Frontend Installation

Follow these steps to set up the frontend of the Todo List App locally.

1. **Clone the repository**:
```
https://github.com/bisht-xp/todo-app.git
```
2. Navigate to the project
```
cd frontend
```
3. Ensure you have npm or yarn installed. Then, run:
```
yarn install or npm install
```
Before starting the project please make sure backend is running (I have added steps to start backend as well)
```
yarn run dev 
```


## Installation

### Prerequisites

Before you begin, ensure you have the following installed on your machine:

- **Node.js** (v14.x or higher)
- **PostgreSQL** (locally or through a service like Supabase)
- **npm** or **yarn**

## Backend Installation

Follow these steps to set up the frontend of the Todo List App locally.

1. **Clone the repository**:

```
https://github.com/bisht-xp/todo-app.git
```

2. Navigate to the project

```
cd backend
```

3. Ensure you have npm or yarn installed. Then, run:

```
yarn install or npm install
```

4. Environment Variables

```
DATABASE_URL="postgresql://user:password@localhost:5432/todolist_db"
PORT=5000
```

5. Prisma setup

```
npx prisma init

npx prisma generate

npx prisma migrate dev --name init
```
6. Running the Application
```
yarn start or npm start
```