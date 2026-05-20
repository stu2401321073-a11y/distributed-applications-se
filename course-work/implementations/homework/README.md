# 🏅 Olympics Management System

## 📌 Project Description
The **Olympics Management System** is a full-stack application developed as a coursework project.  
It consists of a **RESTful Web API** and a **Console Client Application** for managing athletes, competitions, results, and users.

The system supports full CRUD operations, authentication, and structured data management.

---

## 👨‍🎓 Student Information
- **Name:** Dimitar Stoychev
- **Faculty Number:** 2401321073
- **Course:** Software Engineering / Course 2  / Part Time
- **Year:** 2026

---

## ⚙️ Technologies Used

### Backend
- ASP.NET Core Web API
- Entity Framework Core
- SQL Server
- JWT Authentication
- Swagger (OpenAPI)

### Frontend
- C# Console Application
- HttpClient for API communication
- Newtonsoft.Json

---

## 🧩 System Architecture

The project follows a **layered architecture**:

Controllers → Services → Repositories → Database


- Controllers: Handle HTTP requests
- Services: Business logic
- Repositories: Data access layer
- Database: SQL Server

---

## 📦 Main Features

### 👤 Users
- Register / Login / Logout
- Get all users
- Get user by ID
- Update user
- Delete user

### 🏃 Athletes
- Create athlete
- View all athletes
- Get athlete by ID
- Update athlete
- Delete athlete
- Image URL support

### 🏟 Competitions
- Create competition
- View all competitions
- Get competition by ID
- Update competition
- Delete competition
- Image URL support

### 🥇 Results
- Create result
- View all results
- Get result by ID
- Update result
- Delete result
- Track medals, scores, rankings

---

## 🔐 Authentication
The system uses **JWT token authentication**:
- Users must log in to access protected endpoints
- Token is stored in the console client
- Secured API endpoints

---

## 📄 API Documentation
Swagger UI is available at:


https://localhost:5246/swagger


---

## 💻 Console Client Features
- Menu-driven interface
- Full CRUD operations
- API communication via HttpClient
- JSON serialization/deserialization

---

## 🖼 Bonus Features
- Image URL support for all entities
- Clean layered architecture
- DTO pattern (Create / Read / Update)
- JWT authentication system
- Swagger documentation

---

## 🚀 How to Run

### 1. Run API

dotnet run


### 2. Run Console Client

dotnet run


Make sure API is running before starting the client.

---

## 📌 Notes
- The project is designed for educational purposes
- Focus on clean architecture and separation of concerns
- Fully supports CRUD operations for all entities

---

## 📈 Future Improvements
- Image upload system
- Role-based authorization (Admin/User)