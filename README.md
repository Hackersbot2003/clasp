# 🚀 Automation & Analytics Platform  
### (Google Sheets + Apps Script + Clasp + MERN + RBAC)

## 📌 Overview
This project is a **full-stack automation and analytics platform** built using **Google Sheets, Google Apps Script (via Clasp), and the MERN stack**.  
It automates data flow from Google Sheets to a backend system, processes it securely, and displays **role-based analytical dashboards**.

The system focuses on **automation, analytics, and secure access control (RBAC)**, making it suitable for real-world business and enterprise use cases.

---

## ✨ Features

### 🔁 Automation
- Automated data capture from Google Sheets
- Trigger-based execution (onEdit / time-based / API)
- Data validation & transformation
- Secure communication with backend APIs

### 📊 Analytics Dashboard
- Real-time analytical dashboards
- KPI tracking & data visualization
- Role-based data visibility
- Scalable for large datasets

### 🔐 Role-Based Access Control (RBAC)
- Multiple user roles (Admin, Manager, User)
- Permission-based API access
- Secure frontend route protection
- JWT-based authentication

### ⚙️ Backend System
- RESTful APIs using Express.js
- Centralized business logic
- Error handling & logging
- MongoDB for persistent storage

---

## 🏗️ Tech Stack

### Frontend
- React.js
- Charting libraries
- Tailwind CSS / CSS

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication

### Automation
- Google Apps Script
- Clasp (Apps Script CLI)
- Google Sheets API

---

## 🧩 Architecture


---

## 🔐 RBAC Model

| Role | Access Level |
|----|-------------|
| Admin | Full system access |
| Manager | Analytics & limited management |
| User | View assigned data only |

RBAC is enforced at:
- API middleware level
- Database query level
- Frontend route level

---

## 🔁 Automation Workflow

1. Data updated in Google Sheets
2. Apps Script trigger executes
3. Data validated and formatted
4. Secure API call to backend
5. Data stored in MongoDB
6. Dashboard updates in real time

---

## 📈 Analytics Capabilities
- Real-time metrics
- Trend analysis
- Aggregated reports
- Role-specific dashboards

---

## 🔒 Security
- JWT-based authentication
- Role-based authorization
- Secure API endpoints
- Environment variable protection

---

## 🚀 Use Cases
- Payment and transaction tracking
- Business reporting automation
- Operational analytics dashboards
- Enterprise workflow automation
- Hackathon and production systems

---




