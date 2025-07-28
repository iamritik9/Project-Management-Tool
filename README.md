# Project Management Tool

![Project Management Tool Homepage](https://i.ibb.co/wpKt0vZ/PPMT.png)

A full-stack web application for managing personal or team-based projects. Built using ReactJS and Spring Boot, this tool supports user authentication, project tracking, task management, and a project backlog system.

---

## 🔧 Tech Stack

### Frontend (ReactJS)
- React Components & Routing
- Axios for HTTP communication
- React Bootstrap for UI
- JWT Authentication

### Backend (Spring Boot)
- Spring MVC (RestControllers, Services, Repositories)
- JPA & Hibernate
- Spring Security with JWT
- Maven for build management

### Database
- H2 (in-memory, dev only)
- MySQL (for production)

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/en/)
- [Maven](https://maven.apache.org/)
- Java 17 or above

### Setup Instructions

1. **Clone the repository**

```bash
git clone 

2. **Install frontend dependencies**

cd ppmtool-react-client
npm install

3. Build backend package

cd ..
mvn clean package

4.Run Spring Boot application

cd project_management_tool
mvn spring-boot:run

