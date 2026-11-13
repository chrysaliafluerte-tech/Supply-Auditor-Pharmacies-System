# Supply Auditor for Pharmacies System
## 1. Project Title 
Supply Auditor for Pharmacies System
## 2. Project Description
The supply Auditor for Pharmacies System is a Java-based desktop application designed to streamline pharmacy operations. It automates inventory tracking , records customer sales and dispensing transactions, monitors product expiration dates, and facilitates shock audits by comparing  physical counts against system records.
## 3. Problem being addressed
Manual inventory tracking and paper-based logging in pharmacies often lead to human errors, unrecorded stock movements, overlooked product expirations, stock outs, and long, tedious inventory audits. This system solves these issue by providing and automated system for audits.
## 4. Project Objectives
**General Objectives:**
To develop a java-based application that automates pharmacy inventory management, sales tracking, expiration monitoring, and auditing while minimizing  manual recording errors.
**Specific Objectives: **
Implement secure user authentication with role-based access for pharmacists and inventory auditors.
Track medicine stock levels, batch details, and expiration dates in real time.
Automate audit comparisons to instantly flag shortages.
Generate clear reports for sales histories, low stock items and audit summaries.
## 5. Target Users
Pharmacists - Logs daily customer purchases, updates inventory quantities and monitors expiring or low-stock medicines
Inventory Auditor - Conducts periodic inventory  checks, inputs physical counts and reviews automatically generated discrepancy reports.
## 6. Main Features
* User Authentication & Role Management (Pharmacist vs. Auditor)
* Inventory & Batch Management (Categories, prices, batch numbers, and expiry dates)
* Sales & Dispensing Tracker (Real-time stock deduction upon customer purchase)
* Automated Audit & Reconciliation (Calculates variances: Expected Stock = Initial - Sales)
* Expiry & Low-Stock Alert System
* Reporting & Export Dashboard

## 7. Technologies Used
* *Language:* Java
* *Programming Paradigm:* Object-Oriented Programming (OOP)
* *Data Structures:* Java Collections Framework (ArrayList, HashMap)
* *Environment:* Java Development Kit (JDK) / IDE (Eclipse / NetBeans / IntelliJ)

## 8. Team Members and Roles
* *Sion Luis E. Berana* – Lead Programmer
* *Martha S. Gutierrez* – Documentation
* *Allianna H. Lucero* – System and Design Leader
* *Darick Gaile A. Pascua* – Project Leader/ Lead programmer

## 9. OOP Concepts Demonstrated
* *Classes & Objects:* Modeled entities such as Product, SaleRecord, InventoryBatch, Auditor, and AuditRecord.
* *Encapsulation:* Protected sensitive data fields using private modifiers and public getter/setter methods.
* *Inheritance:* Created a base User class extended by specialized subclasses (Pharmacist and Auditor).
* *Polymorphism:* Utilized shared method interfaces for processing different transaction and log types.
* *Abstraction:* Defined clear guidelines for auditing and reporting structures.
* *Exception Handling:* Used try-catch blocks to manage invalid user inputs and prevent program crashes.

## 10. Instructions for Running the Program
1. Clone or download this repository to your local machine.
2. Open your preferred Java IDE (e.g., Eclipse, NetBeans, or IntelliJ IDEA).
3. Import the project folder and make sure the JDK is properly configured.
4. Locate the Main.java file inside the src/ directory.
5. Run Main.java to launch the application.

## 11. Sample Screenshots
//placeholder

## 12. Known Limitations
* The application runs locally as a desktop program and does not feature multi-branch cloud synchronization.
* Barcode/QR code scanning is simulated through keyboard/ID entry unless a physical scanner device is connected.

## 13. Future Improvements
* Integration with a persistent relational database (such as MySQL or SQLite).
* Implementation of hardware barcode scanner support for faster item lookups and sales logging.
* Cloud-based multi-user support for larger pharmacy chains.

## 14. Project Contributors
* Sion Luis E. Berana
* Martha S. Gutierrez
* Allianna H. Lucero
* Darick Gaile A. Pascua
