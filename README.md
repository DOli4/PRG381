# BC Student Wellness Management System (2025 PRG3781 Project)

## Project Overview

This Java-based group project is part of the PRG3781 module at Belgium Campus. The objective is to design and implement a **Student Wellness Management System** with both web and desktop components.

---

## 🔹 Technologies Used

- **Java (Core + OOP)**
- **Java Swing (GUI for desktop app)**
- **JavaDB (for desktop database)**
- **PostgreSQL (for web database)**
- **JSP & Servlets (for web frontend/backend)**

---

## Project Structure

### Milestone 1: Web Application – Login & Registration System (Due: 14 July 2025)

#### Features:
- **JSP Pages**: `index.jsp`, `register.jsp`, `login.jsp`, `dashboard.jsp`
- **Servlets**:
  - `RegisterServlet`: Validates & stores student data in PostgreSQL
  - `LoginServlet`: Authenticates user credentials

#### Functional Requirements:
- Registration:
  - Validates inputs (email, password strength, etc.)
  - Prevents duplicate usernames/emails
  - Stores hashed passwords
- Login:
  - Verifies credentials against PostgreSQL
  - Maintains session state and redirects to dashboard
- Dashboard:
  - Shows personalized welcome
  - Includes logout (session invalidation)
- PostgreSQL Database:
  - `users` table with: `student_number`, `name`, `surname`, `email`, `phone`, `password`
  - Constraints: `NOT NULL`, `UNIQUE` where applicable

---

### Milestone 2: Desktop Application – Wellness Management System (Due: 17 July 2025)

#### Features:
- Java Swing GUI for:
  - Appointment Management
  - Counselor Management
  - Feedback Management
- MVC Architecture
- Full CRUD functionality using **JavaDB**

#### Functional Requirements:

**Appointments:**
- Book, view, update, cancel appointments

**Counselors:**
- Add, view, update, delete counselor info

**Feedback:**
- Submit, view, update, delete feedback

**GUI Expectations:**
- Use of tabs or menus
- Input validation
- Confirmation & error dialogs

---

## Important Notes

- Group of 4 students (auto-assigned)
- All members must understand all Java concepts for presentation
- No plagiarism or AI-generated code
- **Presentation Date: 18 July 2025**

---

## Repository Guidelines

- All work should be pushed to GitHub for version control
- Each member must have a GitHub account
- Commit often and use clear commit messages

---

## Contact

For any issues or collaboration requests, contact the group members or your project supervisor.

---
