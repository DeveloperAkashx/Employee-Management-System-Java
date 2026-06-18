# Employee Management System

A RESTful Employee Management System developed using **Spring Boot**, **Spring Data JPA**, and **MySQL**. This project provides a simple backend application for managing employee records through CRUD (Create, Read, Update, Delete) operations. It demonstrates backend development concepts such as REST APIs, database integration, and layered architecture.

---

## 🚀 Features

- ➕ Add Employee
- 📋 View All Employees
- ✏️ Update Employee Details
- ❌ Delete Employee
- 🗄️ MySQL Database Integration
- 🌐 RESTful API Development
- 🏗️ Layered Architecture (Controller, Service, Repository, Entity)
- 🧪 API Testing using Postman

---

## 🛠️ Tech Stack

- Java 21
- Spring Boot 3
- Spring Data JPA
- MySQL
- Maven
- VS Code
- Postman

---

## 📁 Project Structure

```
employee-management
│
├── controller
│   └── EmployeeController.java
│
├── entity
│   └── Employee.java
│
├── repository
│   └── EmployeeRepository.java
│
├── service
│   └── EmployeeService.java
│
├── EmployeeManagementApplication.java
│
└── application.properties
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/your-username/employee-management-system.git
```

### 2. Open Project

Open the project in **VS Code** or **IntelliJ IDEA**.

### 3. Create MySQL Database

```sql
CREATE DATABASE employee_db;
```

### 4. Configure Database

Open:

```
src/main/resources/application.properties
```

Update your MySQL credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/employee_db
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
```

### 5. Run the Project

Run:

```
EmployeeManagementApplication.java
```

Spring Boot will start on:

```
http://localhost:8080
```

---

## 📌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/employees` | Add Employee |
| GET | `/employees` | Get All Employees |
| PUT | `/employees/{id}` | Update Employee |
| DELETE | `/employees/{id}` | Delete Employee |

---

## 📷 API Testing

The APIs were tested successfully using **Postman**.

Example Response:

```json
[
  {
    "id": 1,
    "name": "Akash Patil",
    "email": "akash@gmail.com",
    "department": "Computer Science"
  }
]
```

---

## 🎯 Learning Outcomes

- Spring Boot Fundamentals
- REST API Development
- CRUD Operations
- Spring Data JPA
- MySQL Integration
- Maven Project Structure
- Backend Development Best Practices

---

## 👨‍💻 Author

**Akash Patil**

- GitHub: https://github.com/DeveloperAkashX
- LinkedIn: https://www.linkedin.com/in/akashpatilprofessional

---

⭐ If you found this project useful, consider giving it a star.
