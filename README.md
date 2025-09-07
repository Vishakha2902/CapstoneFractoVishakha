# CapstoneFractoVishakha
# Fracto - Doctor Appointment System

Fracto is a web application that helps users find doctors, book appointments, and manage medical consultations online. It provides functionality for regular users and admin users to manage doctors and appointments.

## Features

- User registration and login
- Search and browse doctors by specialization
- Book, view, and manage appointments
- Admin dashboard to manage doctors and appointments
- Role-based access control (Admin & User)
- Responsive design using Bootstrap
- JWT Authentication for secure API access

## Project Structure

Fracto/
├── fracto-frontend/       # Angular frontend
├── fracto-backend/        # ASP.NET Core backend API
├── database/              # Database structure or scripts
├── README.md              # Project description (this file)
└── other files...
```

##  Technologies Used

- Frontend: Angular, TypeScript, Bootstrap
- Backend: ASP.NET Core, C#
- Database: SQL Server
- Authentication: JWT
- Version Control: Git

## Installation Instructions

### 1. Backend Setup
- Open the backend project in Visual Studio or VS Code
- Configure `appsettings.json` with your DB connection string and JWT Secret
- Run database migrations if applicable
- Run the API:
  ```bash
  dotnet run
  ```

### 2. Frontend Setup
- Navigate to the frontend folder:
  ```bash
  cd fracto-frontend
  ```
- Install dependencies:
  ```bash
  npm install
  ```
- Run Angular development server:
  ```bash
  ng serve
  ```

---

## Usage

1. Open the browser and go to `http://localhost:4200`
2. Register a new account or log in
3. Search for doctors and book appointments
4. Admins can manage doctors via the dashboard

---

## Configuration

- Make sure to update API URLs in environment files (`environment.ts`)
- Configure JWT Secret key and DB connection string in `appsettings.json`

---



  

GitHub: https://github.com/Vishakha2902/CapstoneFractoVishakha.git
