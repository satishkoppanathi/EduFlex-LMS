# EduFlex LMS – Online Course Management System  
A full-stack Learning Management System built using **React.js**, **Spring Boot**, and **MySQL**, featuring role-based access, secure authentication, assignment handling, and scalable REST APIs.

---

## 🚀 Tech Stack
**Frontend:** React.js, Redux, HTML, CSS, JavaScript, Axios, JWT Auth  
**Backend:** Spring Boot, Spring Security, JWT, Spring Data JPA, REST APIs  
**Database:** MySQL  
**Other:** File Upload/Download, Modular Architecture, Linux Compatible  

---

## 📌 Features

### 🔵 Frontend
- Role-based dashboards (Admin, Instructor, Student)
- CRUD operations: Courses, Users, Instructors, Assignments
- Instructor-wise course filtering
- JWT-based login, auto-redirect on token expiry
- Admin/Private route protection
- Redux for state management
- Real-time success/failure alerts
- Error landing screen when backend is down
- File Upload & Download for assignments
- Password match validation on profile update
- Username availability checking

### 🟢 Backend
- Spring Boot REST APIs for all modules
- Secure authentication using **Spring Security + JWT**
- CRUD operations using Spring Data JPA
- File storage APIs
- Layered architecture (Controller → Service → Repository)
- Fully supports all frontend functionality

---

## 📂 Project Structure
EduFlex-LMS/  
│── backend/ (Spring Boot Application)  
│── frontend/ (React Application)  
└── README.md  

---

## 🧩 Resume Alignment
This project demonstrates:
- Java + Spring Boot backend development  
- REST API design and secure authentication  
- Full-stack development with React.js  
- MySQL database modeling and integration  
- JWT-based role management (Admin, Student, Instructor)  
- Scalable and production-ready architecture  

---

## 🔧 Installation

### Backend:
```bash
cd backend/LecturerCourseDemo
mvn spring-boot:run
```

### Frontend:
```bash
cd frontend
npm install
npm start

## 📜 License
MIT License
