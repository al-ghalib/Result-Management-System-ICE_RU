# Result Management System

This project is a web-based application that allows users to manage and view results efficiently. It is built using **ReactJS** for the frontend and **Django** for the backend.

## Features

- **User Authentication:** Secure login for admin, teachers, and students.
- **Role-based Access Control:** Different roles with appropriate permissions (admin, teacher, student).
- **Result Upload & Management:** Teachers can upload and manage student results.
- **Result Viewing:** Students can view their results by logging in.
- **Responsive Design:** The system is responsive and works well on all devices.

## Tech Stack

### Frontend

- **ReactJS**: A JavaScript library for building user interfaces.
  - React Router for navigation between pages.
  - Axios for handling HTTP requests.
  - Styled Components for styling.
  
### Backend

- **Django**: A high-level Python web framework for rapid development.
  - Django Rest Framework (DRF) for creating APIs.
  - Django's authentication and permission system for security.
  - SQLite as the database.

### Others

- **Axios**: To make HTTP requests from the React frontend to the Django backend.
- **PostgreSQL**: For managing and storing application data.
- **Docker**: (Optional) For containerizing the application.

## Setup & Installation

### Prerequisites

- **Node.js**: Required to run the React frontend.
- **Python 3.x**: Required to run the Django backend.
- **SQLite**: For the database.

### Frontend Setup
   ```bash
   cd frontend
   npm install
   npm run dev
  ```

### Backend Setup
   ```bash
   cd backend
   pip install pipenv
   pipenv install
   pipenv shell
   python manage.py runserver
  ```
