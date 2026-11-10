# library-management-system
# 📚 BibliotecApp

**A Multi-Library Management System with Business Intelligence capabilities.**

BibliotecApp is a web-based platform designed to manage library operations, centralize bibliographic information, control physical book inventories, and analyze library performance through data visualization.

The project aims to provide a scalable solution for multiple libraries, allowing each institution to manage its own resources while enabling global administration and cross-library analytics.

> 🚧 **Project Status:** In Development

---

## 🎯 Project Objectives

- Develop a centralized platform for managing multiple libraries.
- Simplify book cataloging and physical inventory management.
- Manage users, roles, and permissions through Role-Based Access Control (RBAC).
- Track loans, returns, and user sanctions.
- Design a normalized relational database.
- Integrate Business Intelligence (BI) capabilities for operational and strategic analysis.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React |
| Backend | Python / Django |
| Database | PostgreSQL |
| Data Visualization | To be determined |
| Version Control | Git / GitHub |

---

## 🏗️ Core Features

### 1. Multi-Library Management

The system is designed to support multiple libraries within a single platform.

Each library will have its own:
- Users and staff.
- Book inventory.
- Loan records.
- Sanction records.
- Operational statistics.

A global administrator will be able to oversee the platform and access consolidated information across libraries.

### 2. User and Role Management

The platform will implement **Role-Based Access Control (RBAC)**.

Planned roles:

| Role | Description |
|---|---|
| Member | Registered library member who can borrow books. |
| Librarian | Staff member responsible for daily library operations. |
| Manager | Manages a specific library and its resources. |
| Admin | Global administrator with platform-wide access. |

### 3. Bibliographic Management

The system distinguishes between a bibliographic record and its physical copies.

**Book**
- Title
- ISBN
- Publication year
- Publisher
- Language
- Authors
- Genres

**Book Copy**
- Associated book
- Owning library
- Acquisition date and cost
- Topographic signature
- Barcode
- Current condition/status

This separation allows multiple physical copies of the same book to exist across different libraries.

### 4. Loan Management

The platform will provide loan tracking, including:

- Loan registration.
- Scheduled return dates.
- Actual return dates.
- Loan status.
- Complete loan history.

### 5. Sanction Management

The system will keep track of sanctions associated with library members.

Planned sanction categories:
- Late returns.
- Lost books.
- Damaged books.
- Other situations.

A structured catalog of sanction reasons will allow consistent classification and future statistical analysis.

---

## 📊 Business Intelligence

One of the project's main objectives is to incorporate BI capabilities into the platform.

The database is being designed to preserve relevant historical information and support future analytical queries.

### Planned Analytics

**Library Performance**
- Total loans by month and year.
- Most active libraries.
- Comparative performance across libraries.

**Book Analytics**
- Most borrowed books.
- Most popular genres.
- Most frequently borrowed authors.
- Language distribution.

**Inventory Analytics**
- Available, damaged, and lost copies.
- Inventory acquisition costs.
- Annual book losses.
- Inventory turnover.

**User Analytics**
- New user registrations over time.
- Most active members.
- Average member age.
- Sanctions by category.

**Operational Analytics**
- Overdue loan rates.
- Average loan duration.
- Sanction distribution.
- Historical inventory status changes.

---

## 🗄️ Database Design

The database uses a relational approach, following normalization principles and aiming for Third Normal Form (3NF).

