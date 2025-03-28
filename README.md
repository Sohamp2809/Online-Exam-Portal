# Online Exam Portal

A streamlined solution for creating, managing, and taking exams online. This portal uses **Spring Boot + MySQL** on the backend and **React** on the frontend.

---

## Features

### User Management
- Admin can add users, view users, assign roles (candidate, admin), and manage user accounts.

### Question Management
- Create, update, and delete questions for exams.

### Exam/Test Management
- Create new exams, add or remove questions from an exam.

### Candidate Panel
- Users can log in to view available exams and attempt them.

### Results
- Display scores or results after completing exams (optional, depends on your implementation).


---
## Quick Start Commands

Below is a quick, **copy-paste-friendly** set of commands to **clone** the project, **install** dependencies, and **run** both the **backend** (Spring Boot) and **frontend** (React). Just open a terminal and follow along.


### 1. Clone the repository
```
git clone https://github.com/Sohamp2809/Online-Exam-Portal.git
cd Online-Exam-Portal
```
### 2. (Backend) Build & Run with Maven
```
cd backend
mvn clean install
mvn spring-boot:run &
# Backend should start on: http://localhost:8089
```
### 3. (Frontend) Install & Start
```
cd ../frontend
npm install
npm start
# Frontend should run on: http://localhost:3000
```

## Database Configuration (Spring Boot + MySQL)

The project uses **MySQL** configured in [`application.properties`](./backend/src/main/resources/application.properties). If your setup differs, update these lines:

```properties
server.port=8089
spring.datasource.url=jdbc:mysql://localhost:3306/OnlineExamPortal?createDatabaseIfNotExist=true
spring.datasource.username=
spring.datasource.password=
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
```
- **Port**: By default, the backend runs on **8089**.  
- **Credentials**: Replace the username/password with your own.  
- **Database**: Includes `?createDatabaseIfNotExist=true` to auto-create **OnlineExamPortal** if needed.  
- **DDL Auto**: `update` creates/updates tables based on your entity classes.


## Screenshots

### 1. Login

<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/a0aeec22-b13b-411d-b0ce-c18287fe6826"
    alt="Login"
    width="600"
/>
</p>

### 2. User View

<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/751c83a3-95e9-4c4e-9981-2a5895735bbe"
    alt="User View"
    width="600"
/>
</p>


### 3. Question Create

<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/249dabe5-4c2e-4900-b036-674c2184fbb0" 
    alt="Question Create" 
    width="600">
</p>


### 4. Questions

<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/8c81bce4-5768-47c5-80b9-e5225caeb208" 
    alt="Questions" 
    width="600">
</p>

### 5. Test Create
<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/8c2f325d-0715-4b1f-917d-bc91e749bff6" 
    alt="Test Create" 
    width="600">
</p>

### 6. Adding User

<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/79c4a05f-6b98-450e-b8d3-bfb9f9059d0d" 
    alt="Adding User" 
    width="600">
</p>

### 7. Candidate Panel
<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/5ed92ee0-c5eb-4c95-861b-fa1abe6255aa" 
    alt="Candidate Panel" 
    width="600">
</p>

### 8. Exam View
<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/cc45c9cb-ce58-404c-bc01-a523aa2a2d7f" 
    alt="Exam View" 
    width="600">
</p>

---
## Contributing

- Fork the project.

- Create a new branch: `git checkout -b feature/MyNewFeature`.

- Make your changes and commit: `git commit -m "Add my new feature"`.

- Push to the branch: `git push origin feature/MyNewFeature`.

- Open a Pull Request.














