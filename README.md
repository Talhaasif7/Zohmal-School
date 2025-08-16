# School Management System

### Live Demo (optional)
👉 (https://zohmal-school.vercel.app/)

---

## Introduction / Overview

The School Management System is a full-stack web platform designed to digitize and streamline daily school operations such as managing students, teachers, classes, lessons, attendance, exams, assignments, events, and more. It provides dedicated dashboards for Admins, Teachers, Students, and Parents, making communication and data management easier while ensuring real-time updates throughout the school ecosystem.

Built with modern technologies like **Next.js**, **PostgreSQL**, and **Prisma**, the system offers scalability, security, and a clean user experience for all stakeholders.

---

## Goals of the Project

- Digitize major administrative tasks (attendance, grades, schedules, events)
- Provide role-based dashboards with proper access control
- Improve communication between teachers, students, and parents
- Ensure data privacy and security
- Build a responsive, user-friendly interface using modern tools

---

## Architecture Overview

| Layer        | Technology                                      |
|--------------|--------------------------------------------------|
| Frontend     | **Next.js (App Router)**, Tailwind CSS, Clerk    |
| Backend      | Next.js API Routes, Prisma ORM                   |
| Database     | PostgreSQL (via Prisma)                          |
| Deployment   | Vercel (Frontend), Supabase / Railway (Database) |

---

## Tech Stack

Frontend: Next.js, Tailwind CSS, React, Clerk Auth
Backend: Next.js API Routes, Prisma
Database: PostgreSQL
Other Tools: Zod, React Hook Form, Recharts, Cloudinary, TypeScript, Neon

---

## Key Features

### Student Features
- View personal profile, results, attendance, timetable
- View assignments, exams, and announcements
- Keep track of classroom events and updates

### Teacher Features
- Manage classes, lessons, assignments, and exams
- Mark attendance and record student results
- Post announcements for students and parents

### Admin Features
- Full CRUD for Students, Teachers, Parents, Classes, Grades, Subjects, Lessons, etc.
- Assign class supervisors and manage events/announcements
- System-wide control and data overview

### Parent Features
- View child’s attendance, results, and timetable
- Receive announcements and notifications
- Monitor academic performance

---

## Database (PostgreSQL via Prisma)

Main Models:
- Admin
- Teacher
- Student
- Parent
- Class
- Subject
- Lesson
- Exam
- Assignment
- Result
- Attendance
- Grade
- Event
- Announcement

This project uses a relational schema with foreign keys and enums (like `UserSex`, `Day`). The ER diagram below illustrates the table relationships clearly:

> **ERD**  


<img width="2469" height="1485" alt="Untitled" src="https://github.com/user-attachments/assets/26993eb5-79e7-479d-a018-873382049a77" />


## User Journey & Flow

**Student Flow**

Sign Up → Login → Dashboard → View Timetable & Assignments → Check Results/Attendance → Logout


**Teacher Flow**

Login → Dashboard → Manage Lessons / Mark Attendance → Publish Assignments / Exams → Logout


**Parent Flow**

Login → Child Dashboard → Monitor Attendance & Results → Read Announcements → Logout


**Admin Flow**

Login → Admin Dashboard → Manage Users/Classes/Events → Global Announcements → Logout


---

## Best Practices Followed

- 🔐 Secure, role-based authentication (using Clerk)
- ✅ Form validation with Zod & React Hook Form
- ⚙️ Modular and reusable component structure
- 🧠 Prisma ORM with normalized schema and strict relationships
- 🔄 Responsive UI with Tailwind and Next.js App Router
- 📈 Clean Git-based version control with Markdown documentation
- 🧪 Type safety and clean API routes with TypeScript

---

## Author

**Talha Asif**  
Full-Stack Developer | Next.js | Prisma

📧 Email: [talhatoffe7@gmail.com](mailto:talhatoffe7@gmail.com)  
🔗 LinkedIn: [https://www.linkedin.com/in/talha-asif7/](https://www.linkedin.com/in/talha-asif7/)  


---

## License

This project is licensed under the **MIT License**.

---




