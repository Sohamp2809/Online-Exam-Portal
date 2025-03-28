# Online Exam Portal

A streamlined solution for creating, managing, and taking exams online. This portal uses **Spring Boot + MySQL** on the backend and **React** on the frontend.

---

## Features
- **User Management**: Create and manage users (Admin, Candidate).
- **Exam Management**: Create tests, assign questions, set time limits.
- **Question Bank**: Reusable questions categorized by subject.
- **Candidate Panel**: Secure login, view and attempt exams, see results.
- **Scoring**: Automated scoring, results view for admins/candidates.

---
# Quick Start Commands

Below is a quick, **copy-paste-friendly** set of commands to **clone** the project, **install** dependencies, and **run** both the **backend** (Spring Boot) and **frontend** (React). Just open a terminal and follow along.

```bash
# 1. Clone the repository
git clone https://github.com/YourUsername/Online-Exam-Portal.git
cd Online-Exam-Portal

# 2. (Backend) Build & Run with Maven
cd backend
mvn clean install
mvn spring-boot:run &
# The '&' runs Spring Boot in the background
# Backend should start on: http://localhost:8089
# Adjust port in application.properties if needed

# 3. (Frontend) Install & Start
cd ../frontend
npm install
npm start
# Frontend should run on: http://localhost:3000


