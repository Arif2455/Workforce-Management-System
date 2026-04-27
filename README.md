# 🏢 Workforce Management System  

A full-stack web application built using Spring Boot and MySQL to efficiently manage employees and departments with advanced features like search, analytics, and report generation.

---

## 📌 Project Overview  

The Workforce Management System is designed to streamline HR operations by providing a centralized platform to manage employee data, departments, and organizational insights. It includes features such as real-time search, pagination, and export functionality.

---

## 🚀 Features  

### 👨‍💼 Employee Management  
- Add, update, delete, and view employees  
- Assign employees to departments  
- Search by name or email  
- Pagination for large datasets  

### 🏢 Department Management  
- Create, update, and delete departments  
- Manage employee-department relationships  
- Dynamic dropdowns in forms  

### 📊 Advanced Features  
- Export employee data to Excel  
- Generate PDF reports  
- Analytics dashboard with charts (Chart.js)  
- Real-time search and filtering  
- Responsive UI (Bootstrap)  

---

## 🏗️ Tech Stack  

### Backend  
- Spring Boot  
- Spring Data JPA  
- Hibernate  
- Spring Security  

### Frontend  
- HTML5, CSS3, JavaScript  
- Bootstrap  
- Chart.js  

### Database  
- MySQL  

### Tools  
- Maven  
- MySQL Workbench  

---

## 🗂️ Project Structure  

com.example.EmployeeManagementSystem/  
├── config/  
├── controller/  
├── dto/  
├── exception/  
├── mapper/  
├── model/  
├── repository/  
├── service/  
└── validation/  

---

## 🔗 API Endpoints  

### Employee APIs  
GET /api/employee  
POST /api/employee  
PUT /api/employee/{id}  
DELETE /api/employee/{id}  

### Department APIs  
GET /api/departments  
POST /api/departments  
PUT /api/departments/{id}  
DELETE /api/departments/{id}  

### Export APIs  
GET /api/export/excel  
GET /api/export/pdf  

---

## 🧠 Key Concepts Implemented  
- RESTful API design  
- MVC architecture  
- DTO pattern  
- Input validation & exception handling  
- Secure backend with authentication  
- Optimized database queries  

---

## 🛠️ Setup & Installation  

### 1. Clone the repository  
git clone https://github.com/your-username/workforce-management-system.git  
cd workforce-management-system  

### 2. Configure Database  

Update application.properties:  

spring.datasource.url=jdbc:mysql://localhost:3306/ems_db  
spring.datasource.username=your_username  
spring.datasource.password=your_password  

### 3. Run the application  
mvn spring-boot:run  

### 4. Open in browser  
http://localhost:8080  

---

## 📊 Database Schema  

### Employees Table  
- id (PK)  
- first_name  
- last_name  
- email  
- department_id (FK)  

### Departments Table  
- id (PK)  
- name  
- description  
- location  

---

## 🔐 Security & Validation  
- Input validation  
- SQL injection protection (via JPA)  
- XSS protection headers  
- Secure authentication  

---

## 📈 Business Value  
- Centralized employee management  
- Improved HR efficiency  
- Fast search & filtering  
- Professional reporting tools  

---

## 🚀 Future Enhancements  
- Employee profile images  
- Role-based access control  
- Audit logs  
- Email notifications  
- Bulk import/export  

---

## 👨‍💻 Author  
Arif S  

---

## ⭐ Support  
If you like this project, give it a star on GitHub!
