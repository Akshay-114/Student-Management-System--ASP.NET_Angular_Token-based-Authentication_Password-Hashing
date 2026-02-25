# Student Management System

A full-stack Student Management System built using ASP.NET Core Web API (.NET 8) and Angular. This project implements secure authentication, authorization, and CRUD operations following modern best practices.

## Features

- Secure user authentication using PBKDF2 password hashing
- JWT-based authentication with access and refresh tokens
- Automatic token refresh on expiration
- Secure logout by token removal
- Route protection using Angular Auth Guards
- JWT handling using HTTP Interceptors
- Full CRUD operations for student management
- RESTful API architecture

## Tech Stack

### Backend
- ASP.NET Core Web API (.NET 8)
- Entity Framework Core (Code First)
- SQL Server
- JWT Authentication
- PBKDF2 Password Hashing

### Frontend
- Angular
- TypeScript
- RxJS
- Angular Services, Guards, and Interceptors

## Project Structure

student-management-system/
├── backend/   # ASP.NET Core Web API
├── frontend/  # Angular application
└── README.md

## Setup Instructions

### Backend
1. Open the backend project in Visual Studio
2. Update the database connection string in `appsettings.json`
3. Apply migrations
4. Run the API
5. Check using swagger

### Frontend
```bash
npm install
ng serve
