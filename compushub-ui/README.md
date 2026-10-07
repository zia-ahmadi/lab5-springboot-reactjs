# CompusHub — Course & Registration Management System (Frontend)

A responsive multi-page React frontend prototype for **CompusHub**, a university course and registration management system.

> ⚠️ **Note:** This project is the **frontend-only** prototype. It uses **static sample data** and does **not** connect to any backend API yet. API integration (Spring Boot) will be handled in a later lab.

---

## 📚 Course Information

| Field | Detail |
|---|---|
| **Course** | Enterprise Web Applications |
| **Institution** | Faculty of Computer Science, Kabul University |
| **Lab** | Lab Assignment 04 — React UI Setup and Design |
| **Student Name** | _[Your Full Name]_ |
| **Student ID** | _[Your Student ID]_ |
| **Instructor** | _[Instructor Name]_ |
| **Submission Date** | _[DD/MM/YYYY]_ |

---

## 🎯 Lab Objectives

By completing this lab, the following objectives were achieved:

- Created a new React application using **Vite**.
- Understood the basic structure of a React project.
- Installed and configured **Bootstrap** and **React Router**.
- Created reusable React components using **JSX**.
- Built a shared **Navbar** and page **Layout**.
- Configured **client-side routes** for different application screens.
- Designed a **responsive Course Management UI** using Bootstrap.
- Ran and tested the React application in the browser.

---

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|---|---|---|
| **React** | ^18.x | UI library |
| **Vite** | ^5.x | Build tool & dev server |
| **React Router DOM** | ^6.x | Client-side routing |
| **Bootstrap** | ^5.x | Responsive UI framework |
| **JavaScript (ES2020+)** | — | Programming language |
| **ESLint** | — | Code quality & linting |
| **Node.js / npm** | — | Runtime & package manager |

---

---

## 🚦 Application Routes

| Route | Component | Description |
|---|---|---|
| `/` | `Dashboard` | Landing page with app overview |
| `/courses` | `Courses` | Course Management UI (form + static table) |
| `/students` | `Students` | Student management placeholder |
| `/sections` | `Sections` | Section management placeholder |
| `/registrations` | `Registrations` | Registration management placeholder |

> Navigation is done via **React Router `<Link>`** — no full page reloads.

