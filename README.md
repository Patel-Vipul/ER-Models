# Database ER Diagram Assignments

A collection of Entity Relationship Diagram (ERD) assignments completed as part of the **Web Dev Cohort 2026**.

These assignments focus on designing normalized, scalable relational database schemas for real-world systems. Each project models a different business domain and demonstrates database design principles such as normalization, entity relationships, lookup tables, junction tables, and separation of static and operational data.

---

## 📚 Assignments

| # | Project                                       | Description                                                                                                                                               |
| - | --------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1 | **Fitness Influencer Coaching Platform**      | Database design for an online coaching platform supporting trainers, clients, subscriptions, workout plans, diet plans, progress check-ins, and payments. |
| 2 | **Clinic Appointment & Diagnostics Platform** | Models patients, doctors, appointments, consultations, diagnostic tests, reports, and payments for a modern outpatient clinic.                            |
| 3 | **Smart Elevator Control Platform**           | Infrastructure management system for multi-building elevator operations, ride requests, allocations, maintenance, and analytics.                          |
| 4 | **Instagram Thrift Creator Store**            | Database design to sell thrift fashioned items and handmade products.                                                                                                                     |
| 5 | **Comic Con Parking System**                  | Database design to manage vehicles parking efficiently with records of all parking slots and seperation of parking based on the type of vehicels                                                                                                                    |

Each assignment contains:

* 📄 `README.md` explaining the design decisions
* 🗂️ `schema.eraser` source file
* 🖼️ Exported ER diagram (`.svg`)
* 📋 Database schema (DBML/Eraser)

---

## 🧠 Concepts Covered

Throughout these assignments, I practiced designing databases that emphasize:

* Entity Relationship Modeling (ERD)
* Database Normalization (up to 3NF)
* One-to-One Relationships
* One-to-Many Relationships
* Many-to-Many Relationships
* Junction Tables
* Lookup Tables
* Primary & Foreign Keys
* Business Rule Modeling
* Separation of Configuration and Operational Data
* History Tracking (Audit-style tables)
* Scalable Relational Database Design

---

## 🛠️ Tools Used

* **Eraser.io** – ER Diagram Design
* **DBML** – Database Modeling Language
* **Git & GitHub** – Version Control
* **Markdown** – Documentation

---

## 📂 Repository Structure

```text
.
├── fitness-influencer-coaching-platform/
│   ├── README.md
│   ├── schema.eraser
│   └── diagram.svg
│
├── clinic-appointment-diagnostics-platform/
│   ├── README.md
│   ├── schema.eraser
│   └── diagram.svg
│
├── smart-elevator-control/
│   ├── README.md
│   ├── schema.eraser
│   └── diagram.svg
│
├── instagram-thrift-creator-store/
│   ├── README.md
│   ├── schema.eraser
│   └── diagram.svg
│
├── comic-con-parking-system
│   ├── README.md
│   ├── schema.eraser
│   └── diagram.svg
│
└── README.md
```

---

## 🎯 Learning Outcomes

These assignments helped strengthen my understanding of:

* Translating business requirements into relational database models
* Designing scalable schemas for real-world applications
* Identifying entities, relationships, and cardinality
* Choosing when to use lookup tables and junction tables
* Separating static configuration data from transactional data
* Documenting database design decisions clearly

---

## 🚀 About

This repository is part of my journey through the **Web Dev Cohort 2026**, where I'm learning backend engineering and database design by building systems inspired by real-world business domains.

Each project represents a different problem space and focuses on creating clean, maintainable, and scalable relational database designs.
