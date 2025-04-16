## Personalised Task Planner

A full-stack task planner that helps users manage tasks, track progress, visualize tasks on a calendar, and use a sketchpad for visual notes. Built with React (Vite), Express, PostgreSQL, Paper.js, Chart.js and AJAX.

## Features

- Task Management – Add, Edit, Delete, and Mark tasks as completed.
- Calendar Integration – View tasks on a calendar with color-coded deadlines.
- Sketchpad – Draw, and download sketches for study notes.
- Authentication – Secure user registration & login with JWT.
- Task Analytics – Track completed vs pending tasks with charts.
- File Uploads – Attach PDFs, images, docs to tasks.
- Sidebar Navigation – Switch between Dashboard, Calendar, Sketchpad, and Settings.
- Settings Page – Change username, password, and delete account permanently.
- Fully Responsive – Mobile, Tablet, and Desktop compatible.
- Built with Vite – Super-fast frontend with HMR (Hot Module Replacement).

## Technologies

Frontend (React + Vite)

- React.js – UI Framework
- Vite – Fast frontend bundler
- React Router – Navigation
- React Query – API data fetching
- Paper.js – Sketchpad functionality
- AJAX (Fetch API) – Handles file uploads & API requests
- React-big-calendar – Task calendar
  Backend (Express & Node.js)
- Express.js – Backend framework
- PostgreSQL – Database
- jsonwebtoken (JWT) – Authentication
- bcryptjs – Secure password hashing
- Multer – File uploads (tasks & sketches)

## API Endpoints

**Authentication**

Method, Endpoint and Description:

POST -- /auth/register -- Register a new user

POST -- /auth/login -- User login & JWT token

GET -- /auth/me -- Get logged-in user info

**Task Management**

Method, Endpoint and Description:

POST -- /tasks/create -- Add a new task

GET -- /tasks/all -- Get all user tasks

PUT -- /tasks/update/:id -- Update task details

DELETE -- /tasks/delete/:id -- Delete a task

**File Uploads**

Method, Endpoint and Description:

POST -- /tasks/upload -- Upload files for tasks

GET -- /uploads/:file -- Download uploaded files

## Usage Guide

**Task Management**

- Add a Task → Enter title, description, deadline, priority, and category.
- Mark as Complete → Click ✅ to move task to "Completed Tasks."
- Edit or Delete → Click ✏️ to modify, ❌ to remove.
  **Calendar**
- View Tasks by Date → Click on a day to see tasks with deadlines.
- Tasks Change Color → Pending (🔴 Red), Completed (🟢 Green).
  **Sketchpad**
- Draw & Save → Use the canvas to create study notes.
- Undo/Redo → Fix mistakes instantly.
- Download Sketch → Save as .jpg for offline access.
  **Settings**
- Update Username & Password → Change account details securely.
- Delete Account → Removes all data permanently.

## Future Features

- Dark Mode
- Collaboration (Invite others to tasks)
- Reminders (Email notifications)

## Credits

- Developer: Gift Ahanonu
- Languages Used: JavaScript (React, Node.js), SQL, HTML, CSS
