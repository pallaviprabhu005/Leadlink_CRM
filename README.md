# LeadLink CRM 🔗

LeadLink CRM is a Customer Relationship Management (CRM) system developed to help sales teams manage leads, track customer interactions, organize tasks, and monitor sales activities efficiently. The application provides role-based access, lead tracking, task management, and reporting features to improve sales productivity and customer engagement.

## 👥 Team Members

1. Pallavi Prabhu
2. Gayatri Gurugubelli
3. Prakyat Shetty
4. Yasti Kotak

**Project Type:** Academic Team Project

## 🙋 My Contributions

* Developed frontend user interfaces using React.js
* Integrated frontend components with backend APIs
* Worked on lead management and dashboard modules
* Assisted in database design and API testing
* Participated in debugging, validation, and project documentation

## 🚀 Features

* User Authentication & Authorization
* Lead Management System
* Task Tracking and Assignment
* Sales Pipeline Monitoring
* Dashboard Analytics
* Role-Based Access Control
* Customer Interaction Tracking
* Reporting and Data Management

## 🛠️ Technology Stack

### Frontend
* React.js
* HTML5
* CSS3
* JavaScript

### Backend
* Node.js
* Express.js

### Database
* PostgreSQL

### Tools
* Git
* GitHub
* Postman
* VS Code

## 🏗️ System Architecture
```text
Frontend (React.js)
        ↓
 REST APIs
        ↓
Backend (Node.js + Express.js)
        ↓
 PostgreSQL Database
```

The React frontend communicates with the backend through REST APIs. The backend processes requests, performs business logic, and stores or retrieves data from the PostgreSQL database.

## 🚀 Quick Start

### Install Dependencies

```bash
npm install
npm install --prefix server
```

### Setup Database

```bash
npx prisma migrate dev
npm run seed
```

### Start Application

```bash
npm run start:all
```

### Access Application

Frontend:

```text
http://localhost:5173
```

API Documentation:

```text
http://localhost:5000/api/docs
```

## 🔐 User Roles

### Sales Representative

* Manage personal leads
* Track assigned tasks
* Update lead status

### Manager

* View team performance
* Manage team leads
* Generate reports
* Delete leads

### Admin

* View audit logs
* Monitor system activities
* Manage platform settings

## 📂 Project Structure

```text
LeadLinkCRM/
├── src/
│   ├── api/
│   ├── components/
│   ├── contexts/
│   └── utils/
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── prisma/
│   └── routes/
│
└── package.json
```

## 🎯 Project Objectives

* Simplify lead management for sales teams
* Improve customer relationship tracking
* Provide role-based access and security
* Increase sales team productivity
* Centralize customer and sales information

## 📚 Key Learnings

Through this project, we gained practical experience in:

* Frontend development using React.js
* Backend API development using Node.js and Express.js
* Database management with PostgreSQL
* REST API integration
* Authentication and authorization
* Team collaboration using Git and GitHub

## 📄 License

This project was developed for educational and learning purposes.

Built with ❤️ by Team LeadLink CRM
