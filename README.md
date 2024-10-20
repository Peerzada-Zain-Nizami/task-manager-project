# Task Manager Frontend (React.js)

This is the frontend for the Task Manager application, built with **React.js**.

## Prerequisites

Make sure you have the following installed:

- Node.js 14.x or higher
- npm or Yarn

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/task-manager-project.git
   cd task-manager-project/frontend
Install dependencies:

bash
Copy code
npm install
Update API URL:

Open src/config.js (or wherever the API URL is stored).
Set the base URL to point to the Laravel backend (e.g., http://localhost:8000/api).
Start the development server:

bash
Copy code
npm start
The frontend will be running at http://localhost:3000.

Environment Variables
To connect to the backend API, ensure the correct API base URL is set in your src/config.js file:

javascript
Copy code
const API_BASE_URL = "http://localhost:8000/api";
export default API_BASE_URL;
Features
User Authentication:
Login and register users using the API.
JWT-based authentication to secure routes.
Task Management:
List, create, update, and delete tasks.
Pages
Login Page: Allows users to log in using their email and password.
Task Page: Displays the list of tasks with options to add, update, or delete tasks.
