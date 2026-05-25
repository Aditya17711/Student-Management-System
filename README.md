# 🎓 Student Management System

A modern full-stack web application built using **Spring Boot** and **MySQL** to efficiently manage student records with complete CRUD operations.

Designed with clean architecture, scalable backend structure, and an intuitive user experience — making it a strong beginner-to-intermediate full-stack development project.

---

## 🚀 Highlights

✅ Full CRUD Functionality  
✅ RESTful Backend Architecture  
✅ MVC-Based Project Structure  
✅ Responsive User Interface  
✅ Database Integration with MySQL  
✅ Beginner-Friendly & Industry-Relevant Project  

---

## 🏗️ Architecture

```text
┌─────────────────────────────────────────────────────┐
│                   CLIENT (Browser)                  │
│             HTML + CSS + Thymeleaf                  │
└────────────────────────┬────────────────────────────┘
                         │ HTTP Requests
┌────────────────────────▼────────────────────────────┐
│              SPRING BOOT APPLICATION                │
│                                                     │
│   ┌──────────────┐    ┌──────────────┐              │
│   │  Controller  │───▶│   Service    │              │
│   │   (Routes)   │    │ (Business    │              │
│   └──────────────┘    │   Logic)     │              │
│                        └──────┬───────┘              │
│                               │                      │
│                        ┌──────▼───────┐              │
│                        │  Repository  │              │
│                        │ (Spring JPA) │              │
│                        └──────┬───────┘              │
└───────────────────────────────┼──────────────────────┘
                                │
┌───────────────────────────────▼──────────────────────┐
│                  MYSQL DATABASE                      │
│             students • courses • records             │
└──────────────────────────────────────────────────────┘
```

---

## 🧩 Project Structure

```text
Student-Management-System/
│
├── .idea/                          # IntelliJ IDEA config
│
└── Student-management-system/
    │
    ├── src/
    │   └── main/
    │       ├── java/
    │       │   └── com/example/sms/
    │       │       ├── controller/      # HTTP request handlers
    │       │       ├── model/           # Entity/data models
    │       │       ├── repository/      # Database access layer
    │       │       ├── service/         # Business logic
    │       │       └── Application.java # Main entry point
    │       │
    │       └── resources/
    │           ├── templates/           # Thymeleaf views
    │           ├── static/              # CSS, JS, Images
    │           └── application.properties
    │
    └── pom.xml                          # Maven configuration
```

---

## 🛠️ Tech Stack

| Technology   | Usage                     |
| ------------ | ------------------------- |
| Java         | Backend Development       |
| Spring Boot  | Application Framework     |
| MySQL        | Database                  |
| HTML/CSS     | Frontend UI               |
| Bootstrap    | Responsive Design         |
| Thymeleaf    | Server-Side Rendering     |
| Maven        | Dependency Management     |

---

## 📌 Features

- Add Student Records
- Update Existing Student Data
- Delete Student Entries
- View All Students
- Responsive & Clean User Interface
- MySQL Database Connectivity
- MVC-Based Backend Structure

---
## Demo
<img width="2048" height="1135" alt="image" src="https://github.com/user-attachments/assets/d529fb2a-296e-4227-bb9d-9ac169a44df0" />
<img width="2545" height="1421" alt="image" src="https://github.com/user-attachments/assets/8e40126f-32e9-4f07-8e59-4c749036d5c0" />
<img width="2554" height="1423" alt="image" src="https://github.com/user-attachments/assets/fb38559d-f072-4377-9d2c-390c77cdf5d3" />
<img width="2557" height="1419" alt="image" src="https://github.com/user-attachments/assets/84bfc7c4-a999-458b-b86c-bc692c523b75" />




---

## ⚙️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/Aditya17711/Student-Management-System.git
cd Student-Management-System
```

---

### Configure MySQL Database

Create a database:

```sql
CREATE DATABASE student_management;
```

Update database credentials inside:

```properties
src/main/resources/application.properties
```

Example configuration:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/student_management
spring.datasource.username=your_username
spring.datasource.password=your_password
```

---

### Run the Application

```bash
mvn spring-boot:run
```

---

## 🌐 Application URL

```bash
http://localhost:8080
```

---

## 📚 Learning Outcomes

This project helped in understanding:

- Spring Boot Fundamentals
- MVC Architecture
- CRUD Operations
- Database Connectivity
- Backend Development Workflow
- Full-Stack Project Structure
- Repository & Service Layer Pattern

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome.

Feel free to fork the repository and submit pull requests.

---

## 👨‍💻 Developer

**Aditya Kumar**

🔗 GitHub:  
https://github.com/Aditya17711

🔗 Repository:  
https://github.com/Aditya17711/Student-Management-System
