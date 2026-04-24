# 🎓 Nova Academy – Academic Management System

<p align="center">
  <img src="https://img.shields.io/badge/Frontend-React%20%2B%20TypeScript-61dafb?style=for-the-badge&logo=react" />
  <img src="https://img.shields.io/badge/Backend-Laravel-ff2d20?style=for-the-badge&logo=laravel" />
  <img src="https://img.shields.io/badge/Database-MySQL-00758f?style=for-the-badge&logo=mysql" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" />
</p>

<p align="center">
  A modern and scalable academic management platform built with a powerful full-stack architecture.
</p>

---

## 🚀 Overview

Nova Academy is a full-stack web application designed to simplify academic management for institutions.
It provides tools for administrators, teachers, and students in one unified platform.

---

## ✨ Key Features

🔐 **Authentication & Security**

* Secure authentication (JWT / Sanctum)
* Role-Based Access Control (Admin, Teacher, Student)
* Protected routes and session handling

🏛️ **Admin Dashboard**

* Manage users, courses, and classes
* View analytics and statistics
* Centralized timetable management

👨‍🏫 **Teacher Panel**

* Manage grades and student performance
* Access assigned courses
* View personal schedule

🎓 **Student Panel**

* Track grades and academic progress
* Access courses and timetable
* Interactive dashboard

---

## 🛠 Tech Stack

| Layer    | Technology                           |
| -------- | ------------------------------------ |
| Frontend | React, TypeScript, Vite, TailwindCSS |
| Backend  | Laravel, MySQL, REST API             |
| Tools    | Git, npm, Composer                   |

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/ilyasslourik-ux/nova-academy.git
cd nova-academy
```

### 2. Backend setup

```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
```

### 3. Frontend setup

```bash
cd frontend
npm install
npm run dev
```

---

## 📸 Preview

<p align="center">
  <img src="https://via.placeholder.com/800x400?text=Dashboard+Preview" />
</p>

---

## 📁 Project Structure

```
backend/   → Laravel API
frontend/  → React Application
```

---

## 🔒 Security

* Secure authentication & authorization
* Input validation and protection
* Safe API communication

---

## 🚀 Future Improvements

* Real-time notifications
* Mobile application (React Native)
* PDF reports generation

---

## 👨‍💻 Author

**Ilyass Lourik**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
