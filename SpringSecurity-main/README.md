# 🔐 Spring Security + JWT Authentication Demo

This project demonstrates how to implement authentication and authorization using Spring Security and JSON Web Tokens (JWT) in a RESTful API.

It showcases how users can securely log in and access protected resources by passing a Bearer Token in the Authorization header.

---

## 🚀 Features

- User Authentication using Email & Password
- JWT Token Generation on Login
- Stateless Session Management
- Secure REST APIs using Spring Security
- Role-based Authorization (optional extension)
- MySQL / PostgreSQL Database Integration
- Password Encryption using BCrypt

---

## 🛠️ Tech Stack

- Java 17+
- Spring Boot
- Spring Security
- JWT (JSON Web Token)
- Hibernate / JPA
- MySQL / PostgreSQL
- Maven

---

## 📁 Project Structure

com.agam.rest_example
│
├── Controller
├── Service
├── Repository
├── Entity
├── Security
└── Config

---

## 🔑 Authentication Flow

1. User sends login request with credentials
2. Server validates user using Spring Security
3. JWT token is generated
4. Token is returned to client
5. Client sends token in Authorization header for protected APIs
6. Server validates token before granting access

---

## 📌 API Endpoints

### 🔓 Public Endpoints

POST /register

POST /login


---

### 🔒 Protected Endpoints

GET /api/students/{id}

Headers:
Authorization: Bearer <your_jwt_token>

---

## 🧪 Testing with Postman

1. Login using /api/auth/login
2. Copy token
3. Use it in Authorization header for protected APIs

---

## 🔐 Security Configuration

- CSRF disabled
- Stateless session
- JWT filter added before UsernamePasswordAuthenticationFilter
- BCrypt password encoding

---
## Screenshots

<img width="1440" height="900" alt="Screenshot 2026-04-02 at 9 28 38 AM" src="https://github.com/user-attachments/assets/9a591bce-844e-4d20-a8b1-5dc686fb56dc" />

<img width="957" height="680" alt="573380258-4cf88b6a-49c3-4e20-81c8-99e33911d076" src="https://github.com/user-attachments/assets/8fc4231b-0e3a-4e31-8a76-9f36936cd5db" />


![864a4097-4022-4e42-a6fb-7f0a00a94aeb](https://github.com/user-attachments/assets/b86e63f5-19fc-4597-bd2c-a036f341b323)


![4cada1fe-70cc-4ba3-a12f-e11cc7e36f23](https://github.com/user-attachments/assets/0a0c479d-fa6a-49da-a759-02c9e06120c6)






---

## ▶️ How to Run

git clone https://github.com/your-username/your-repo.git
cd your-repo
mvn spring-boot:run

---

## 👨‍💻 Author

Soumay Soni
