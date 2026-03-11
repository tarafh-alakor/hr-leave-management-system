# HR Leave Management System

## Overview

The **HR Leave Management System** is a Java-based application designed to help Human Resources departments manage employee leave requests, contracts, and employee records efficiently.

The system aims to replace manual HR processes such as spreadsheets and paper records with an automated system that allows employees and HR staff to manage leave requests, track leave balances, and generate reports.

This project was developed across multiple university courses and demonstrates the **complete software development lifecycle**, including system analysis, software engineering implementation, user interface design, and advanced Java GUI development.

---

## Problem Statement

Managing employee leave, contracts, and attendance manually creates several challenges for HR departments. Manual systems often lead to:

* Errors in leave tracking
* Delays in approving leave requests
* Missing contract expiration dates
* Difficulty retrieving employee records
* Inefficient data management using spreadsheets

These issues can lead to operational delays and inaccurate HR records. The goal of this project is to design a centralized HR system that automates these processes.

---

## Proposed Solution

The HR Leave Management System provides a structured platform that allows HR staff to manage employee information, handle leave requests, track leave balances, and generate reports.

The system provides:

* Employee information management
* Leave request submission and tracking
* Leave balance monitoring
* Contract management
* Reporting services

The system improves efficiency, reduces human error, and simplifies HR operations.

---

## Project Development Stages

This project was developed through multiple phases as part of different software engineering courses.

### 1. System Analysis and Design

During this phase, the system requirements were gathered and analyzed.

Key activities included:

* Identifying HR management problems
* Conducting stakeholder interviews
* Defining functional and non-functional requirements
* Creating system models and diagrams

Design artifacts include:

* Data Flow Diagrams (DFD)
* Use Case Diagrams
* Written Use Cases
* System Requirements Documentation

These artifacts describe how data flows through the system and how users interact with the application.

---

### 2. Software Engineering Implementation

The system was implemented using **Java** and object-oriented programming principles.

The application was structured into multiple classes that represent core HR entities and services.

Key classes include:

* `Employee.java` – Represents employee records
* `LeaveRequest.java` – Manages employee leave requests
* `LeaveBalance.java` – Tracks available leave balances
* `Contract.java` – Manages employee contract information
* `HR_System.java` – Main system controller
* `ReportService.java` – Generates reports for HR operations
* `EntitleLeave_System.java` – System entry point

The implementation focuses on modular design and separation of responsibilities.

---

### 3. User Interface Design (HCI)

The user interface was designed to improve usability for HR staff.

This phase included:

* User research and interviews
* Identifying HR workflow challenges
* Designing user personas and scenarios
* Creating UI prototypes and interface layouts

The goal was to design an intuitive interface that simplifies HR tasks such as managing employees and reviewing leave requests.

---

### 4. Advanced Programming Implementation

The final phase of the project involves implementing a **GUI-based Java application** as part of the Advanced Programming course.

The development is organized into multiple phases.

#### Phase 2 – GUI Design (**Completed**)

During this phase, the graphical user interface of the system was designed and implemented in Java.

All required frames were created to represent the main system interfaces and navigation flow. At this stage, the focus was on designing the layout and interaction between frames without implementing full backend functionality.

The GUI currently includes interfaces such as:

* **Sign In**
* **Sign Up**
* **Password Recovery**
* **Dashboard**
* **Employee Management**
* **Leave Request Management**
* **Reporting Interface**

These frames define how users will interact with the system once the full functionality is implemented.

#### Phase 3 – Functional Implementation (**In Progress**)

The next phase focuses on implementing the system functionality and integrating it with the graphical interfaces.

This stage will apply several advanced programming concepts learned in the course, including:

* Exception handling
* File I/O streams
* Concurrent programming
* Network programming
* Database connectivity

The goal of this phase is to transform the current GUI structure into a **fully functional HR Leave Management desktop application**.

---

## System Features

The HR Leave Management System provides several core features:

* Employee record management
* Leave request submission
* Leave approval and tracking
* Leave balance management
* Contract tracking
* HR reporting functionality
* User authentication and login system

These features support HR departments in managing employee-related operations efficiently.

---

## Technologies Used

The project uses the following technologies:

* Java
* Object-Oriented Programming (OOP)
* Java GUI development
* Software Engineering design principles
* System Analysis and UML modeling

---

## Project Structure

```
hr-leave-management-system
│
├── README.md
│
├── system-analysis
│   └── system-analysis-report.pdf
│
├── software-engineering
│   ├── design-report.pdf
│   └── project
│       ├── Employee.java
│       ├── LeaveRequest.java
│       ├── LeaveBalance.java
│       ├── Contract.java
│       ├── HR_System.java
│       ├── EntitleLeave_System.java
│       └── ReportService.java
│
├── ui-design
│   └── ui-prototype.pdf
│
├── advanced-programming
│   ├── gui-design.pdf
│   └── java-source-code
```

---

## Future Improvements

Several improvements could be implemented in future versions of the system:

* Database integration for persistent data storage
* Role-based access control for HR managers and employees
* Email notifications for leave approvals
* Automated contract expiration alerts
* A web-based version of the application

These improvements would make the system more scalable and suitable for real-world HR environments.

---

## Author

Amal Aljohani
Information Technology Student
