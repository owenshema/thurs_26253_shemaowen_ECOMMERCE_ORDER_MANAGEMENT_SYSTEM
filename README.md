# E-Commerce Order Management System

👤 **Student Info**  
Name: Shema Owen  
Student ID: 26253  
Course: Database Development with PL/SQL (INSY 8311)  
Instructor: Eric Maniraguha  
Academic Year: 2024–2025  

---

## 📌 Problem Statement  
The current order management processes in many e-commerce platforms lack automation, traceability, and enforcement of business rules. This project addresses the need for a robust, PL/SQL-driven system that ensures secure, efficient, and auditable handling of orders and customer interactions.

---

## 🛠️ Objectives  
- Automate order processing using PL/SQL procedures and functions.  
- Enforce business rules using triggers and packages.  
- Restrict sensitive operations based on date/time and holidays.  
- Implement auditing to track user actions and ensure data integrity.

---

## 🧱 Technologies Used  
- Oracle PL/SQL  
- SQL Developer  
- GitHub for version control and reporting

---

## 📂 Project Phases  

### Phase I: Initial Setup  
- Created core tables and inserted sample data.  
- Added initial SQL scripts and documentation files.  

### Phase II: Business Process Modeling  
- Documented business processes and workflows for the order system.  
- [Phase II Business Process Modeling Document](Phase_II_Business_Process_Modeling_Shema_Owen.docx)

### Phase III: Logical Model Design  
- Developed ER diagram and related documentation.  
- ![ER Diagram](ER_%20_diagram.png)  
- [Phase III Ecommerce ER Model](PhaseIII_Ecommerce_ER_Model_ShemaOwen.docx)

### Phase IV: Database Management  
- Configured tablespaces and pluggable database setup.  
- ![Phase 4 OEM Tablespaces](Phase%204%20OEM%20TABLESPACES.png)  
- ![Phase 4 OEM Container](phase%204%20OEM%20CONTAINER.png)  
- ![Phase 4 Pluggable Database](phase%204%20pluggable%20database.png)

### Phase V: DML and Business Logic  
- Inserted data and developed key tables for orders, products, customers, shipment, payment, and order approval.  
- Screenshots:  
  ![Phase 5 Inserting](phase%205%20Inserting.png)  
  ![Phase 5 DML](phase%205%20dml.png)  
  ![Phase 5 Table Manager](phase%205%20table%20manager.png)  
  ![Phase 5 Table Order](phase%205%20table%20order.png)  
  ![Phase 5 Table Order Approval](phase%205%20table%20order_approval.png)  
  ![Phase 5 Table Payment](phase%205%20table%20payement.png)  
  ![Phase 5 Table Product](phase%205%20table%20product.png)  
  ![Phase 5 Table Shipment](phase%205%20table%20shipment.png)

### Phase VI: PL/SQL Programming  
- Created functions, procedures, and triggers for business rules enforcement and automation.  
- Screenshots:  
  ![Phase 6 Function](phase%206%20function.png)  
  ![Phase 6 Procedure](phase%206%20procedure.png)  
  ![Phase 6 Trigger](phase%206%20trigger.png)

### Phase VII: Advanced Programming & Auditing  
- Developed auditing packages and triggers for logging user activity and enforcing restrictions.  
- Screenshots:  
  ![Phase 7 Audit](phase7%20audit.png)  
  ![Phase 7 Holidays](phase7%20holidays.png)  
  ![Phase 7 Package Audit](phase7%20package%20audit.png)  
  ![Phase 7 Restriction](phase7%20restriction.png)  
  ![Table Audit](table%20audit.png)  
- [Advanced DB Programming Auditing Presentation](Phase_VII_Advanced_DB_Programming_Auditing.pptx)

---

## 📄 Major SQL Files  

| File Name          | Description                         |
|--------------------|-----------------------------------|
| create_tables.sql   | DDL scripts to create core tables |
| insert_data.sql     | DML scripts to populate sample data|
| order_pkg.sql       | Package for order processing       |
| triggers.sql       | Restriction and auditing triggers  |
| functions.sql       | Utility functions                  |
| audit_log.sql       | Audit table creation and logic    |

---

## 📈 Results Summary  
- Orders restricted on holidays and weekdays (triggers tested).  
- Orders and products processed and retrieved via packages.  
- Auditing successfully tracks all attempted changes.

---

## 🔚 Conclusion  
This project demonstrates how advanced PL/SQL features can be applied to build a real-world, secure, and audit-compliant e-commerce system. It enforces business rules, promotes automation, and maintains integrity through database programming.

---

> “Whatever you do, work at it with all your heart, as working for the Lord, not for human masters.” — Colossians 3:23
