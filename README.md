# 🎓 ClassBuddy — Your Academic Companion

ClassBuddy is a full-stack academic management platform built to enhance classroom coordination and productivity. Designed for both students and teachers/class representative, it provides a seamless dashboard experience, smart reminders, role-based access control, and dynamic scheduling. 
As a Class Representative, I experienced the challenges of managing announcements, reminders, and schedules across multiple WhatsApp groups. ClassBuddy centralizes this workflow — enabling teachers and CRs of each section to manage announcements, class schedules, and reminders in one place.

The platform is scalable across an entire campus, ensuring that:
- Students can access only their respective department, year, and section.
- Teachers and CRs can manage only their assigned sections.
- Data is isolated, secure, and contextually relevant for each user.

![WhatsApp Image 2025-06-02 at 22 48 37_7995e4c7](https://github.com/user-attachments/assets/69573bfc-23cc-4529-8ad4-f3a120b600a6)

![WhatsApp Image 2025-06-02 at 22 48 37_e067a034](https://github.com/user-attachments/assets/1c83bcd2-788b-4ee2-b888-789717f1fe5a)

![WhatsApp Image 2025-06-02 at 22 48 37_0ecf82e4](https://github.com/user-attachments/assets/5ae4fd9d-1f93-4954-8a6a-5c93368a1ccd)

![WhatsApp Image 2025-06-02 at 22 48 37_295e3c25](https://github.com/user-attachments/assets/89ae2a7b-0c13-4dac-93d4-2353fbc48182)

![WhatsApp Image 2025-06-02 at 22 48 37_5eb79e89](https://github.com/user-attachments/assets/7a08f530-08a7-44a4-916a-f2c8750cbdb0)

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
