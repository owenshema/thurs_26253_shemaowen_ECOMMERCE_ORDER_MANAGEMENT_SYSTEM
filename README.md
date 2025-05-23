# E-Commerce Order Management System

---

## 👤 Student Info  
**Name:** Shema Owen  
**Student ID:** 26253  
**Course:** Database Development with PL/SQL (INSY 8311)  
**Instructor:** Eric Maniraguha  
**Academic Year:** 2024–2025  

---

## 📌 Problem Statement  
Many e-commerce platforms face challenges with manual order processing, lack of automation, limited traceability, and weak enforcement of business rules. This project builds a robust, PL/SQL-based system that ensures secure, efficient, and auditable order management.

---

## 🛠️ Objectives  
- Automate order processing using PL/SQL procedures and functions  
- Enforce business rules with triggers and packages  
- Restrict sensitive operations during holidays and specific timeframes  
- Implement auditing to log user actions for accountability and data integrity  

---

## 🧱 Technologies Used  
- Oracle PL/SQL  
- SQL Developer  
- GitHub for version control and documentation  

---

## 📂 Project Phases  

### Phase I: Initial Setup  
- Created core tables and inserted sample data  
- Added initial SQL scripts and documentation files  

### Phase II: Business Process Modeling  
- Documented order management business processes  
- [Phase II Business Process Modeling Document](./Phase_II_Business_Process_Modeling_Shema_Owen.docx)  

### Phase III: Logical Model Design  
- Developed ER diagram and related documentation  
- [ER Diagram Image](./ER_diagram.png)  
- [Phase III Ecommerce ER Model Document](./PhaseIII_Ecommerce_ER_Model_ShemaOwen.docx)  

### Phase IV: Database Management  
- Configured tablespaces and pluggable database environment  
- [Phase 4 OEM Tablespaces](./Phase_4_OEM_TABLESPACES.png)  
- [Phase 4 OEM Container](./phase_4_OEM_CONTAINER.png)  
- [Phase 4 Pluggable Database](./phase_4_pluggable_database.png)  

### Phase V: DML and Business Logic  
- Inserted data and developed tables for orders, products, customers, shipments, payments, and order approvals  
- Screenshots:  
  - [Phase 5 Inserting](./phase_5_inserting.png)  
  - [Phase 5 DML](./phase_5_dml.png)  
  - [Phase 5 Table Manager](./phase_5_table_manager.png)  
  - [Phase 5 Table Order](./phase_5_table_order.png)  
  - [Phase 5 Table Order Approval](./phase_5_table_order_approval.png)  
  - [Phase 5 Table Payment](./phase_5_table_payment.png)  
  - [Phase 5 Table Product](./phase_5_table_product.png)  
  - [Phase 5 Table Shipment](./phase_5_table_shipment.png)  

### Phase VI: PL/SQL Programming  
- Developed functions, procedures, and triggers to automate business rules  
- Screenshots:  
  - [Phase 6 Function](./phase_6_function.png)  
  - [Phase 6 Procedure](./phase_6_procedure.png)  
  - [Phase 6 Trigger](./phase_6_trigger.png)  

### Phase VII: Advanced Programming & Auditing  
- Implemented auditing packages and triggers to track user actions and enforce restrictions  
- Screenshots:  
  - [Phase 7 Audit](./phase7_audit.png)  
  - [Phase 7 Holidays](./phase7_holidays.png)  
  - [Phase 7 Package Audit](./phase7_package_audit.png)  
  - [Phase 7 Restriction](./phase7_restriction.png)  
  - [Table Audit](./table_audit.png)  
  - [Advanced DB Programming Auditing Presentation](./Phase_VII_Advanced_DB_Programming_Auditing.pptx)  

---

## 📄 Major SQL Files  
| File Name           | Description                          |  
|---------------------|------------------------------------|  
| create_tables.sql    | DDL scripts to create core tables  |  
| insert_data.sql      | DML scripts to populate sample data|  
| order_pkg.sql        | Package for order processing        |  
| triggers.sql         | Restriction and auditing triggers   |  
| functions.sql        | Utility functions                   |  
| audit_log.sql        | Audit table creation and logic     |  

---

## 📈 Results Summary  
- Orders are restricted during holidays and specific weekdays (tested triggers)  
- Automated processing of orders and products through packages  
- Comprehensive auditing logs all attempted data modifications  

---

## 🔚 Conclusion  
This project demonstrates the power of Oracle PL/SQL to build a secure, automated, and auditable e-commerce order management system, enforcing business rules and promoting data integrity throughout.

---

> “Whatever you do, work at it with all your heart, as working for the Lord...” — Colossians 3:23  
