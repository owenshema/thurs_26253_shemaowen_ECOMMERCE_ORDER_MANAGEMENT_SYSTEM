# E-Commerce Order Management System

## 👤 Student Info
- **Name:** Shema Owen  
- **Student ID:** 26253  
- **Course:** Database Development with PL/SQL (INSY 8311)  
- **Instructor:** Eric Maniraguha  
- **Academic Year:** 2024–2025  

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
- [ER Diagram](ER_diagram.png)  
- [Phase III Ecommerce ER Model](PhaseIII_Ecommerce_ER_Model_ShemaOwen.docx)

### Phase IV: Database Management  
- Configured tablespaces and pluggable database setup.  
- [Phase 4 OEM Tablespaces](Phase_4_OEM_TABLESPACES.png)  
- [Phase 4 OEM Container](phase_4_OEM_CONTAINER.png)  
- [Phase 4 Pluggable Database](phase_4_pluggable_database.png)

### Phase V: DML and Business Logic  
- Inserted data and developed key tables for orders, products, customers, shipment, payment, and order approval.  
- Screenshots:  
  - [Phase 5 Inserting](phase_5_Inserting.png)  
  - [Phase 5 DML](phase_5_dml.png)  
  - [Phase 5 Table Manager](phase_5_table_manager.png)  
  - [Phase 5 Table Order](phase_5_table_order.png)  
  - [Phase 5 Table Order Approval](phase_5_table_order_approval.png)  
  - [Phase 5 Table Payment](phase_5_table_payement.png)  
  - [Phase 5 Table Product](phase_5_table_product.png)  
  - [Phase 5 Table Shipment](phase_5_table_shipment.png)

### Phase VI: PL/SQL Programming  
- Created functions, procedures, and triggers for business rules enforcement and automation.  
- Screenshots:  
  - [Phase 6 Function](phase_6_function.png)  
  - [Phase 6 Procedure](phase_6_procedure.png)  
  - [Phase 6 Trigger](phase_6_trigger.png)

### Phase VII: Advanced Programming & Auditing  
- Developed auditing packages and triggers for logging user activity and enforcing restrictions.  
- Screenshots:  
  - [Phase 7 Audit](phase7_audit.png)  
  - [Phase 7 Holidays](phase7_holidays.png)  
  - [Phase 7 Package Audit](phase7_package_audit.png)  
  - [Phase 7 Restriction](phase7_restriction.png)  
  - [Table Audit](table_audit.png)  
- [Advanced DB Programming Auditing Presentation](Phase_VII_Advanced_DB_Programming_Auditing.pptx)  

---

## 📄 Major SQL Files  
| File Name          | Description                               |  
|--------------------|-------------------------------------------|  
| `create_tables.sql` | DDL scripts to create core tables         |  
| `insert_data.sql`   | DML scripts to populate sample data       |  
| `order_pkg.sql`     | Package for order processing               |  
| `triggers.sql`      | Restriction and auditing triggers          |  
| `functions.sql`     | Utility functions                          |  
| `audit_log.sql`     | Audit table creation and logic             |

---

## 📸 Screenshots  
Screenshots for each phase and output results are located in the repository root (or a `/screenshots` folder if you prefer).

---

## 📈 Results Summary  
- Orders restricted on holidays and weekdays (triggers tested).  
- Orders and products processed and retrieved via packages.  
- Auditing successfully tracks all attempted changes.

---

## 🔚 Conclusion  
This project demonstrates how advanced PL/SQL features can be applied to build a real-world, secure, and audit-compliant e-commerce system. It enforces business rules, promotes automation, and maintains integrity through database programming.

---

> “Whatever you do, work at it with all your heart, as working for the Lord...” — Colossians 3:23
