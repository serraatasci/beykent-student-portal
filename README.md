# Beykent University – Integrated Student Portal Project

##  Project Overview
This project aims to design an **integrated digital student portal** for Beykent University by unifying multiple existing academic and administrative systems into a **single, user-friendly platform**.  
Currently, students access different services through separate systems (OBS, Pusula, exam platforms, e-library, payment systems, etc.), which causes usability issues and inefficiencies.  
This project proposes a **centralized and modular solution** to improve accessibility, data consistency, and user experience.

---

##  Project Objectives
- Combine all student-related services into **one unified platform**
- Reduce system fragmentation and repetitive administrative work
- Improve user experience for students and academic staff
- Ensure data integrity, security, and scalability
- Provide a modern and maintainable system architecture

---

##  Development Methodology
**Classical Waterfall Model** was selected because:
- System requirements are stable and clearly defined
- University academic rules rarely change
- Strong emphasis on analysis, documentation, and design
- Suitable for projects involving sensitive academic and financial data

---

##  System Architecture
The system is designed using a **3-Tier Architecture**:
1. **Presentation Layer** – User interface (mobile/web client)
2. **Business Logic Layer** – Server-side processing and RESTful APIs
3. **Data Layer** – Centralized relational database

This structure improves security, maintainability, and scalability.

---

##  Core Modules
- Student Information System (courses, grades, attendance)
- Exam Information System
- Course Material Management
- E-Library Integration
- Student Support & Help Desk
- Preparatory School Module
- Payment & Financial Transactions
- Academic Calendar
- Announcements & Notifications
- Technical Support System

---

##  Database Design
Relational database structure designed for data integrity and secure access.

Main entities include:
- Student
- Course
- Attendance
- Exam
- Grade
- CourseMaterial
- AcademicCalendar
- Payment
- Announcement

All sensitive data access is handled through the business logic layer.

---

##  Technologies Used
- **Frontend:** Flutter (Dart)
- **Backend:** Node.js (Express) / Python (REST API)
- **Database:** PostgreSQL
- **Design & Prototyping:** Figma
- **Version Control:** Git & GitHub

---

##  Cost Considerations
- Open-source technologies are used to eliminate license costs
- Main costs are limited to development and maintenance
- Expected reduction in administrative workload and paper usage
- Long-term operational efficiency and sustainability

---

##  Security Considerations
- Role-based access control (student, academic staff, admin)
- Centralized authentication system
- Sensitive data protected via layered architecture
- Secure handling of academic and financial records

---

## 📂 Repository Structure
