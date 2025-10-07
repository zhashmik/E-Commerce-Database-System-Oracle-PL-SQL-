#  E-Commerce Database System (Oracle PL/SQL)

##  Project Overview
A comprehensive **E-Commerce Database System** built using **Oracle SQL and PL/SQL**, designed to manage end-to-end online retail operations.  
The project implements a **multi-package architecture** integrating complex business rules, validation mechanisms, and automated triggers to ensure data accuracy and seamless transaction flow.

---

##  Key Functional Areas
- **User Management:** registration, authentication, account updates, and customer profile tracking.  
- **Product Management:** product insertion, pricing updates, stock monitoring, and catalog search.  
- **Order Processing:** order creation, modification, cancellation, and fulfillment tracking.  
- **Payment Handling:** transaction logging, refund management, and invoice generation.  
- **Shipping & Logistics:** shipment scheduling, tracking, and delivery confirmation.  

---

##  Technical Implementation
- **Packages:** modularized PL/SQL architecture with over 25 procedures and functions encapsulated across packages like `PKG_USERS`, `PKG_PRODUCTS`, `PKG_ORDERS`, `PKG_PAYMENTS`, and `PKG_SHIPMENTS`.  
- **Functions:** data retrieval utilities (e.g., total sales, active users, pending shipments).  
- **Procedures:** workflow automation (e.g., generating invoices, processing refunds, updating stock).  
- **Triggers:** automated stock updates, order validation, and audit logging.  
- **Exception Handling:** centralized exception tracking using custom error codes and messages.  

---

##  Highlights
- Implemented transactional consistency using COMMIT, ROLLBACK, and savepoints.  
- Designed referential integrity with foreign key constraints and cascading updates.  
- Automated core workflows — order validation, stock updates, and payment reconciliation.  
- Enhanced modularity through reusable PL/SQL packages, making the system maintainable and scalable.  

---

##  Technology Stack
- **Oracle SQL / PL/SQL**  
- **Oracle SQL Developer / SQL*Plus**  
- **Relational Database Design (3NF)**  
- **Triggers, Packages, Procedures, Functions, Exception Handling**

---

##  How to Run
Direct Execution in SQL*Plus:

- Open SQL*Plus and connect to your Oracle database.
- Run the script
- Set server output to view procedure results

---


