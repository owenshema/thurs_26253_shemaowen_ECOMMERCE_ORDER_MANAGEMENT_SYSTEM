
# E-Commerce Order Management System

## 👤 Student Info
- **Name:** Shema Owen  
- **Student ID:** 26253  
- **Course:** Database Development with PL/SQL (INSY 8311)  
- **Instructor:** Eric Maniraguha  
- **Academic Year:** 2024–2025  

## 📌 Problem Statement
The current order management processes in many e-commerce platforms lack automation, traceability, and enforcement of business rules. This project addresses the need for a robust, PL/SQL-driven system that ensures secure, efficient, and auditable handling of orders and customer interactions.

## 🛠️ Objectives
- Automate order processing using PL/SQL procedures and functions.
- Enforce business rules using triggers and packages.
- Restrict sensitive operations based on date/time and holidays.
- Implement auditing to track user actions and ensure data integrity.

## 🧱 Technologies Used
- Oracle PL/SQL
- SQL Developer
- GitHub for version control and reporting

## 🗂️ Key Features
- **Stored Procedures**: Automate order creation and item handling.
- **Functions**: Calculate totals and retrieve dynamic data.
- **Triggers**: Restrict modifications during weekdays/public holidays.
- **Packages**: Bundle related procedures and functions.
- **Auditing Mechanism**: Logs user actions (user, date/time, operation, status).
- **GitHub Documentation**: All scripts and screenshots are documented.

## 📸 Screenshots
Screenshots of each phase and output results are located in the `screenshots/` folder.

## 📄 Major SQL Files
| File Name | Description |
|-----------|-------------|
| `create_tables.sql` | DDL scripts to create core tables |
| `insert_data.sql` | DML scripts to populate sample data |
| `order_pkg.sql` | Package for order processing |
| `triggers.sql` | Restriction and auditing triggers |
| `functions.sql` | Utility functions |
| `audit_log.sql` | Audit table creation and logic |

## 📈 Results Summary
- Orders restricted on holidays and weekdays (triggers tested).
- Orders and products processed and retrieved via packages.
- Auditing successfully tracks all attempted changes.

## 🔚 Conclusion
This project demonstrates how advanced PL/SQL features can be applied to build a real-world, secure, and audit-compliant e-commerce system. It enforces business rules, promotes automation, and maintains integrity through database programming.

## 🔗 Repository Link
[https://github.com/owenshema/thurs_26253_shemaowen_E_COMMERCE-ORDER-MANAGEMENT-SYSTEM](https://github.com/owenshema/thurs_26253_shemaowen_E_COMMERCE-ORDER-MANAGEMENT-SYSTEM)

> “Whatever you do, work at it with all your heart, as working for the Lord...” — Colossians 3:23
