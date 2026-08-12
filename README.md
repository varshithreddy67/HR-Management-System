# 🏢 HR Management System

A backend-based **HR Management System** developed using **Java and Spring Boot** to manage employees, departments, and user authentication through secure REST APIs.

## 📌 Project Overview

The HR Management System provides RESTful APIs for managing HR-related data. It follows a layered architecture to keep the application organized, maintainable, and scalable.

The project includes user authentication using **Spring Security and JWT**, employee and department management, database integration, and API documentation using Swagger.

## 🚀 Features

- 🔐 JWT-based User Authentication
- 👤 User Login and Role Management
- 👨‍💼 Employee Management
- 🏢 Department Management
- ➕ Create Employee/Department records
- 🔍 Retrieve Employee/Department records
- ✏️ Update Employee/Department records
- 🗑️ Delete Employee/Department records
- 🛡️ Spring Security-based API protection
- 🗄️ MySQL Database Integration
- 📚 Swagger/OpenAPI API Documentation

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java | Programming Language |
| Spring Boot | Backend Framework |
| Spring Security | Authentication & Authorization |
| JWT | Token-based Authentication |
| Spring Data JPA | Database Operations |
| Hibernate | ORM |
| MySQL | Database |
| Maven | Dependency Management |
| Swagger / OpenAPI | API Documentation |
| IntelliJ IDEA | Development Environment |
| Postman | API Testing |

## 🏗️ Project Architecture

The project follows a layered architecture:

```text
Controller
    ↓
Service
    ↓
Service Implementation
    ↓
Repository
    ↓
Entity
    ↓
MySQL Database
<img width="1345" height="623" alt="image" src="https://github.com/user-attachments/assets/4309368f-4335-4579-8cb9-8e7b26b74bcf" />
<img width="825" height="636" alt="image" src="https://github.com/user-attachments/assets/e173c99a-14e9-490f-ad77-f86a807e7b11" />
<img width="596" height="647" alt="image" src="https://github.com/user-attachments/assets/7ec69c75-d92f-4159-a949-505c2d30e5f9" />
<img width="1025" height="642" alt="image" src="https://github.com/user-attachments/assets/fae966b0-c767-4161-a302-5a9d6b13dd61" />
<img width="1182" height="642" alt="image" src="https://github.com/user-attachments/assets/50b1af11-fb26-42ae-a4eb-87d9fd2ea120" />
