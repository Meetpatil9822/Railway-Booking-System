# 🚆 Railway Booking System

A multitier, full-stack railway ticketing platform built with **Java**, **JSP**, **MySQL**, and **JDBC** — featuring separate portals for customers, administrators, and sales representatives, with role-based access control, concurrent seat reservation logic, and banking-grade security.

---

## ✨ Features

### 👤 Customer Portal
- User signup, login, and profile management
- Train search, seat reservation, booking history & cancellation
- Station schedules and train details

### 🛠️ Admin Portal
- Schedule management, revenue reports, customer analytics
- Transit analysis, QA system, data backup tools

### 🧑‍💼 Sales Rep Portal
- Rep dashboard and management tools

### 🔒 Security
- Role-based access control (RBAC)
- Parameterized queries (SQL injection prevention)
- Input validation and encryption for sensitive data

---

## 🛠️ Tech Stack
| Layer | Technology |
|---|---|
| Language | Java |
| Frontend | JSP, HTML/CSS |
| Backend | Java Servlets |
| Database | MySQL |
| DB Connectivity | JDBC |
| App Server | Apache Tomcat 9/10 |
| Architecture | Multitier MVC |

---

## 🏗️ README.mdArchitecture
```
┌─────────────────────────────────────┐
│        Presentation Layer            │
│   JSP Pages + index.html (UI Views) │
├─────────────────────────────────────┤
│        Business Logic Layer          │
│   Java Servlets & Controllers       │
├─────────────────────────────────────┤
│        Data Access Layer             │
│   JDBC + MySQL (DAO Pattern)        │
└─────────────────────────────────────┘
```

---

## 🧪 Key Engineering Challenges
- **Concurrency** — Transaction locking for simultaneous reservations with zero double-bookings
- **Multi-role system** — Three fully separate portals with strict RBAC enforcement
- **ACID compliance** — Partial bookings automatically rolled back on failure
- **Security hardening** — Parameterized queries, input sanitization across all flows

---

## 👤 Author
**Meet Patil**
- LinkedIn: [linkedin.com/in/meet-patil-a174692a2](https://www.linkedin.com/in/meet-patil-a174692a2/)
- GitHub: [github.com/Meetpatil9822](https://github.com/Meetpatil9822)
