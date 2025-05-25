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



### Phase IV: Database Management  
- Configured tablespaces and pluggable database environment  
- ![Phase_4 OEM_TABLESPACES](https://github.com/user-attachments/assets/8e355300-4bcf-417f-b391-1798d575ba1c)
  
- ![OEM Container](./Phase_4_Physical_DB_Implementation/phase_4_OEM_CONTAINER.png)  
![phase 4 pluggable database](https://github.com/user-attachments/assets/70926825-3daa-40c1-9473-7cb932873ad4)
  

### Phase V: DML and Business Logic  
- Developed tables and inserted data for orders, products, customers, shipments, payments, and approvals  
- ![Inserting](./Phase_5_DML_and_Queries/phase_5_Inserting.png)  
- ![DML](./Phase_5_DML_and_Queries/phase_5_dml.png)  
- ![Table Manager](./Phase_5_DML_and_Queries/phase_5_table_manager.png)  
- ![Table Order](./Phase_5_DML_and_Queries/phase_5_table_order.png)  
- ![phase_5 table_order_approval](https://github.com/user-attachments/assets/634d27a1-3f84-47cb-8170-ae7b2cad32c3)

- ![phase_5_table_payement](https://github.com/user-attachments/assets/6bf6347c-a176-4e3e-a6ca-5c7d3a38a0e0)
 
- ![phase _5_table_product](https://github.com/user-attachments/assets/76e13887-0b5c-4ef2-96de-c5822dc8f646)
 
- ![phase_5_table_shipment](https://github.com/user-attachments/assets/276a950c-759b-4f9a-9e32-f1285e91dab7)
  

### Phase VI: PL/SQL Programming  
- Built procedures, functions, and triggers for business automation  
- ![Function](./Phase_6_DB_Programming/phase_6_function.png)  
- ![Procedure](./Phase_6_DB_Programming/phase_6_procedure.png)  
- ![Trigger](./Phase_6_DB_Programming/phase_6_trigger.png)  

### Phase VII: Advanced Programming & Auditing  
- Implemented audit mechanisms and security restrictions  
- ![phase_7_audit](https://github.com/user-attachments/assets/2d597fc6-c136-407a-a33f-dfefb07ce907)
 
- ![phase_7_holidays](https://github.com/user-attachments/assets/f3fd226c-c5a9-4646-8eed-f9863f07a8f4)
 
- ![Package Audit](./Phase_7_Security_Auditing_And_Advanced/phase7_package_audit.png)  
- ![Restriction](./Phase_7_Security_Auditing_And_Advanced/phase7_restriction.png)  
- ![phase7_table_audit](https://github.com/user-attachments/assets/940535a3-441f-4936-b037-d868dcba2c65)
 
-  

---

## conclusion
The E-Commerce Order Management System successfully automates the order processing workflow and secures data integrity using robust PL/SQL features. Triggers and packages effectively enforce complex business logic, while the comprehensive auditing mechanism provides valuable insights for Management Information System (MIS) functions.



---


   
