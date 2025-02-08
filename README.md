# Dating App

This is a modern dating application developed using **Angular** for the frontend and **ASP.NET Core API with Entity Framework** for the backend. The application provides user authentication, profile management, matchmaking, and messaging functionalities.

## Project Structure

### 1. Frontend - Angular
- Developed using **Angular** framework for a responsive and dynamic user interface.
- Utilizes **Angular Material** for UI components.
- Communicates with the backend API via **HTTP services**.
- Implements **JWT-based authentication**.

### 2. Backend - ASP.NET Core API
- Built using **ASP.NET Core Web API** to handle business logic and database operations.
- Uses **Entity Framework Core** for data persistence and interaction with the database.
- Implements **JWT authentication and authorization** for secure access.
- Provides RESTful endpoints for users, profiles, matches, and messages.

### 3. Database
- Uses **SQL Server** as the relational database.
- Entity Framework Core **Code-First Migrations** is used for database schema management.

## Features
- **User Authentication**: Registration, Login, and JWT-based authentication.
- **User Profiles**: Manage personal details, upload profile pictures, and update interests.
- **Matchmaking**: Algorithm to suggest potential matches.
- **Messaging System**: Real-time messaging between matched users.
- **Profile Search**: Search for users based on preferences.
- **Admin Panel**: Manage users, reports, and other administrative tasks.

## Setup Instructions

### 1. Prerequisites
- Install **Node.js** and **Angular CLI**.
- Install **.NET SDK** (latest version supporting ASP.NET Core).
- Set up **SQL Server** and ensure it's running.

### 2. Frontend Setup
```sh
cd frontend
npm install
ng serve
```

### 3. Backend Setup
```sh
cd backend
dotnet restore
dotnet ef database update
dotnet run
```

### 4. Configuration
- Update `environment.ts` in Angular with the correct **API URL**.
- Update `appsettings.json` in the backend with the correct **database connection string**.

## Technologies Used
- **Frontend**: Angular, TypeScript, Angular Material, RxJS
- **Backend**: ASP.NET Core, Entity Framework Core, JWT Authentication
- **Database**: SQL Server
- **Tools**: Postman, Swagger, VS Code, Visual Studio

## Summary
This dating app provides a robust matchmaking experience with a user-friendly interface, secure authentication, and real-time messaging. Follow the setup instructions to deploy and start using the application.

