# 🚀 JobPortal - Full Stack Job Management Application

JobPortal is a full-stack web application designed to manage job postings efficiently. 
The application provides RESTful APIs for creating, retrieving, updating, and managing job listings with a Spring Boot backend and a responsive user interface.

## 📌 Features

- ✅ Create new job postings
- ✅ View all available job listings
- ✅ Search and manage job details
- ✅ RESTful API integration
- ✅ Layered architecture using Controller, Service, and Repository layers
- ✅ Database persistence using Spring Data JPA and Hibernate
- ✅ Responsive web interface
- ✅ MVC-based frontend using JSP
- ✅ PostgreSQL database integration

## 🛠️ Tech Stack

### Backend
- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate
- REST APIs
- Maven

### Frontend
- React.js
- JavaScript
- Axios
- Material UI
- HTML5
- CSS3

### Database
- PostgreSQL

### Tools
- IntelliJ IDEA
- Postman
- Git & GitHub

## 🏗️ Project Architecture
JobPortal
│
├── Controller Layer
│ └── Handles HTTP requests and REST endpoints
│
├── Service Layer
│ └── Contains business logic
│
├── Repository Layer
│ └── Handles database operations using JPA
│
├── Model Layer
│ └── Defines Job entities
│
└── Database
└── PostgreSQL

## 🔗 API Endpoints

### Get All Jobs
GET /jobposts
Returns all available job postings.

---
### Get Job By ID
GET /jobpost/{id}
Returns job details based on job ID.

---
### Add New Job
POST /jobpost
Creates a new job posting.
Example Request:

json
{
  "postId": 1,
  "postProfile": "Java Developer",
  "postDesc": "Looking for Spring Boot Developer",
  "reqExperience": 2,
  "postTechStack": [
    "Java",
    "Spring Boot",
    "Hibernate"
  ]
} 

---------
### Delete a Job
DELETE /jobpost/{id}
---------

🔮 Future Enhancements
User authentication and authorization using Spring Security
Recruiter and candidate roles
Job application tracking system
Cloud deployment
Email notifications
👨‍💻 Author

Lokesh Goud

B.Tech Computer Science Engineering (Data Science)

GitHub:
https://github.com/Lokeshgoud2109
