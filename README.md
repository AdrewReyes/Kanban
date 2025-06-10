# Kanban Board Full-Stack Application

## Description

A full-stack Kanban board application built with React, Express, TypeScript, and PostgreSQL. The app features secure authentication using JWT, allowing users to log in, view, create, and manage tickets assigned to users. The backend uses Sequelize ORM for database interaction.

---

## Features

- User authentication with JWT
- Secure login/logout flow
- Kanban board with tickets sorted by status (Todo, In Progress, Done)
- Create, assign, and update tickets
- PostgreSQL database with Sequelize models
- Protected API routes

---

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- PostgreSQL
- npm

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/your-repo-name.git
   cd 14-Full-Stack-React/02-Challenge/Develop
   
### Set up environment variables:

Create a .env file in server/ with the following:
   -DB_NAME=your_db_name
   -DB_USER=your_db_user
   -DB_PASSWORD=your_db_password
   -DB_HOST=localhost
   -JWT_SECRET=your_jwt_secret

### Deployment
**This application is ready to deploy on Render:**

Set up a PostgreSQL database on Render and add the connection details to your server's environment variables.
Deploy the app as a web service, using the following build and start commands:
Build Command: npm install && npm run build
Start Command: npm start
After deployment, use the Render Shell to run npm run seed to populate the database.   

## Usage
Visit the deployed URL.
Log in with a valid username and password.
Manage your Kanban board tasks.

## License
ISC

## License
Andrew Reyes

## Link
https://kanban-usg8.onrender.com

![image](https://github.com/user-attachments/assets/34c9f275-eac0-4a3f-9cf0-2af84fef3ebb)

