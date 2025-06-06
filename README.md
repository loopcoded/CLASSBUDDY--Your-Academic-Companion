# 🎓 ClassBuddy — Your Academic Companion

ClassBuddy is a full-stack academic management platform built to enhance classroom coordination and productivity. Designed for both students and teachers/class representative, it provides a seamless dashboard experience, smart reminders, role-based access control, and dynamic scheduling. 
As a Class Representative, I experienced the challenges of managing announcements, reminders, and schedules across multiple WhatsApp groups. ClassBuddy centralizes this workflow — enabling teachers and CRs of each section to manage announcements, class schedules, and reminders in one place.

The platform is scalable across an entire campus, ensuring that:
- Students can access only their respective department, year, and section.
- Teachers and CRs can manage only their assigned sections.
- Data is isolated, secure, and contextually relevant for each user.


![WhatsApp Image 2025-05-30 at 18 13 16_ea847379](https://github.com/user-attachments/assets/94212bb2-d94e-499f-b38a-09c6b3822241)
![WhatsApp Image 2025-05-30 at 18 07 31_7c9c27a0](https://github.com/user-attachments/assets/ca466828-a40a-46f2-96bc-52610092efff)
![WhatsApp Image 2025-05-30 at 18 17 30_8afc0091](https://github.com/user-attachments/assets/e4d719ce-ecd9-426c-acce-05be94da1632)
![WhatsApp Image 2025-05-30 at 18 18 50_597b143e](https://github.com/user-attachments/assets/8020fa1b-937b-4301-8a14-6379af60ab77)
![WhatsApp Image 2025-05-30 at 18 50 19_37082e77](https://github.com/user-attachments/assets/ba68e086-ae4a-477c-89aa-2c45a6d03b18)

---

## 🚀 Features

### ✅ Dashboard Overview
- At-a-glance view of today's classes, announcements, and reminders
- Tabbed interface for classes, announcements, and tasks
- Responsive layout built with React + Tailwind CSS

### 📅 Class Schedule Management
- Daily, weekly, and monthly calendar views
- Color-coded visual representation of classes
- Detailed class cards with time, location, and instructor

### 📢 Announcement System
- Urgent and regular announcements
- Filter by category (classes, events, important)
- Set reminders for announcements

### ⏰ Reminders & Tasks
- Priority-based reminders for assignments and events
- Due date & time support
- Completion tracking and management

### 🔐 Authentication & Access
- JWT authentication with role-based access control
- Separate interfaces for Students and Teachers/Class Representative
- Secure login and registration flows

---

## 🧑‍💻 Tech Stack

| Layer         | Technology                       |
|---------------|-----------------------------------|
| Frontend      | React, Tailwind CSS, Axios        |
| Backend       | Node.js, Express.js               |
| Database      | MongoDB + Mongoose                |
| Auth          | JWT (JSON Web Token)              |
| Deployment    | Vercel (frontend),Render(backend) |

---

## 🛠️ Project Structure
```bash
/ClassBuddy
├── frontend/ # React + Tailwind UI
│ ├── src/
│ ├── public/
│ └── ...
├── backend/ # Node.js + Express API
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── ...
├── .gitignore
└── README.md
