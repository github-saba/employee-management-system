# Employee Management System (React + Spring Boot + MySQL)

A secure full-stack enterprise-style application for managing employee records, built using React,
 Spring Boot, and MySQL with JWT-based authentication and role-based authorization.

---

## Features
- Add, update, and delete employees
- View employee list
- Secure authentication using JWT
- Role-based authorization (Admin/User)
- RESTful API integration
- Backend validation and business logic
- Protected routes and API endpoints

---

## Tech Stack

### Frontend
- React
- JavaScript
- Bootstrap

### Backend
- Java
- Spring Boot
- Spring Security
- JWT Authentication
- Spring Data JPA / Hibernate

### Database
- MySQL

---

## Security Features
- JWT-based authentication
- Role-based access control (RBAC)
- Secure API endpoints
- Password encryption

---

## Project Structure
```
ems-application/
│
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── services/
│ │ ├── App.js
│ │ └── index.js
│
├── backend/
│ ├── src/main/java/
│ │ ├── controller/
│ │ ├── service/
│ │ ├── repository/
│ │ ├── dto/
│ │ ├── entity/
│ │ ├── config/
│ │ ├── security/
│ │ └── exception/
│ ├── application.properties
│
└── README.md
```
---

## Installation

### Backend
```
cd backend
mvn spring-boot:run
```
### Frontend
```
cd frontend
npm install
npm start
```

## API Example
```
POST /api/auth/login
POST /api/auth/register

GET /api/employees
POST /api/employees
PUT /api/employees/{id}
DELETE /api/employees/{id}
```
## Purpose

This project demonstrates:

Full-stack enterprise application development
Secure API design using Spring Security and JWT
Role-based authorization implementation
Clean architecture with DTO pattern
Database interaction using JPA/Hibernate

## Author

Gnanaparvathan Sabapathy

