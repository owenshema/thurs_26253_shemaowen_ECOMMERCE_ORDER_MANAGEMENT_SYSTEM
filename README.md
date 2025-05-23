# E-Commerce Order Management System

👤 **Student Info**  
- Name: Shema Owen  
- Student ID: 26253  
- Course: Database Development with PL/SQL (INSY 8311)  
- Instructor: Eric Maniraguha  
- Academic Year: 2024–2025  

---

## Table of Contents

- [Problem Statement](#problem-statement)  
- [Objectives](#objectives)  
- [Technologies Used](#technologies-used)  
- [Project Phases](#project-phases)  
- [Major SQL Files](#major-sql-files)  
- [Usage Instructions](#usage-instructions)  
- [Results Summary](#results-summary)  
- [Conclusion](#conclusion)  

---

## Problem Statement

Many e-commerce platforms face challenges with manual order processing, lack of automation, limited traceability, and weak enforcement of business rules. This project builds a robust, PL/SQL-based system that ensures secure, efficient, and auditable order management.

---

## Objectives

- Automate order processing using PL/SQL procedures and functions  
- Enforce business rules with triggers and packages  
- Restrict sensitive operations during holidays and specific timeframes  
- Implement auditing to log user actions for accountability and data integrity  

---

## Technologies Used

- Oracle PL/SQL  
- SQL Developer  
- GitHub for version control and documentation  

---

## Project Phases

### Phase I: Initial Setup  
- Created core tables and inserted sample data  
- Added initial SQL scripts and documentation files  

### Phase II: Business Process Modeling  
- Documented order management business processes  
- 📄 [Business Process Modeling Document](./Phase_2_Business_Process_Modeling/Phase_II_Business_Process_Modeling_Shema_Owen.docx)  

### Phase III: Logical Model Design  
- Developed ER diagram and related documentation  
- ![ER Diagram](./Phase_3_Logical_Modeling/ER_diagram.png)  
- 📄 [ER Model Document](./Phase_3_Logical_Modeling/PhaseIII_Ecommerce_ER_Model_ShemaOwen.docx)  

### Phase IV: Database Management  
- Configured tablespaces and pluggable database environment  
- ![Tablespaces](./Phase_4_Physical_DB_Implementation/Phase_4_OEM_TABLESPACES.png)  
- ![OEM Container](./Phase_4_Physical_DB_Implementation/phase_4_OEM_CONTAINER.png)  
- ![Pluggable DB](./Phase_4_Physical_DB_Implementation/phase_4_pluggable_database.png)  

### Phase V: DML and Business Logic  
- Developed tables and inserted data for orders, products, customers, shipments, payments, and approvals  
- ![Inserting](./Phase_5_DML_and_Queries/phase_5_Inserting.png)  
- ![DML](./Phase_5_DML_and_Queries/phase_5_dml.png)  
- ![Table Manager](./Phase_5_DML_and_Queries/phase_5_table_manager.png)  
- ![Table Order](./Phase_5_DML_and_Queries/phase_5_table_order.png)  
- ![Table Order Approval](./Phase_5_DML_and_Queries/phase_5_table_order_approval.png)  
- ![Table Payment](./Phase_5_DML_and_Queries/phase_5_table_payment.png)  
- ![Table Product](./Phase_5_DML_and_Queries/phase_5_table_product.png)  
- ![Table Shipment](./Phase_5_DML_and_Queries/phase_5_table_shipment.png)  

### Phase VI: PL/SQL Programming  
- Built procedures, functions, and triggers for business automation  
- ![Function](./Phase_6_DB_Programming/phase_6_function.png)  
- ![Procedure](./Phase_6_DB_Programming/phase_6_procedure.png)  
- ![Trigger](./Phase_6_DB_Programming/phase_6_trigger.png)  

### Phase VII: Advanced Programming & Auditing  
- Implemented audit mechanisms and security restrictions  
- ![Audit](./Phase_7_Security_Auditing_And_Advanced/phase7_audit.png)  
- ![Holidays](./Phase_7_Security_Auditing_And_Advanced/phase7_holidays.png)  
- ![Package Audit](./Phase_7_Security_Auditing_And_Advanced/phase7_package_audit.png)  
- ![Restriction](./Phase_7_Security_Auditing_And_Advanced/phase7_restriction.png)  
- ![Table Audit](./Phase_7_Security_Auditing_And_Advanced/table_audit.png)  
- 📊 [Presentation](./Phase_7_Security_Auditing_And_Advanced/Phase_VII_Advanced_DB_Programming_Auditing.pptx)  

---

## Major SQL Files

| File Name          | Description                          |
|--------------------|--------------------------------------|
| `create_tables.sql` | DDL scripts to create core tables    |
| `insert_data.sql`   | DML scripts to populate sample data  |
| `order_pkg.sql`     | Package for order processing         |
| `triggers.sql`      | Restriction and auditing triggers    |
| `functions.sql`     | Utility functions                    |
| `audit_log.sql`     | Audit table creation and logic       |

---

## Usage Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/owenshema/thur_26253_shemaowen_ECOMMERCE_ORDER_MANAGEMENT.git
   cd thur_26253_shemaowen_ECOMMERCE_ORDER_MANAGEMENT
