# hospital-management-system
📌 Project Overview
The Online Hospital Management System (HMS) is a full-stack web application designed to streamline the management of hospital operations. This includes the handling of patient records, doctor appointments, staff details, billing, and more. The system provides a user-friendly interface for administrators, doctors, and patients to interact with the system efficiently.

This project was developed as part of a Java development course and demonstrates real-world implementation of backend and frontend integration, database connectivity, and role-based functionality.

🔧 Technologies Used
Backend: Java, Spring Boot, Hibernate

Frontend: HTML, CSS, JavaScript, Bootstrap (or Thymeleaf if used)

Database: MySQL

Tools: Eclipse/IntelliJ IDEA, Postman, Git, GitHub, MySQL Workbench

Build Tool: Maven

🎯 Core Features
👨‍⚕️ Admin Module
Admin login authentication

Manage doctors (Add, Update, Delete)

Manage patients (View details, delete if necessary)

Manage staff and departments

View appointment lists and billing records

🩺 Doctor Module
Doctor login

View assigned appointments

View and update patient medical records

Add notes and prescriptions

🧑‍💼 Patient Module
Patient registration and login

Book appointments with available doctors

View prescription history and billing information

💰 Billing Module
Generate bills based on treatment and services

View billing history for each patient

Add new charges, discounts, etc.

🛠️ How We Built It
1. Database Design
Created MySQL tables for:

patients

doctors

appointments

staff

departments

bills

Used foreign keys to maintain relationships (e.g., each appointment linked to patient and doctor)

2. Backend Development
Set up a Spring Boot project using Maven.

Created models/entities for each table using Hibernate annotations.

Developed RESTful APIs using Spring MVC controllers.

Applied service and repository layers to follow good project architecture (Service-Repository pattern).

Integrated validation, exception handling, and role-based access controls.

3. Frontend Development
Designed pages using HTML, CSS, and Bootstrap for responsiveness.

Connected frontend to backend APIs using AJAX/JavaScript or Thymeleaf (depending on the approach).

Developed separate dashboards for admin, doctors, and patients.


4. Testing
Used Postman to test all REST APIs.

Checked all edge cases (like booking with unavailable doctors, duplicate patients, etc.)

Handled backend errors gracefully and displayed user-friendly messages

Folder Structure 
src/
 └── main/
     ├── java/
     │   └── com.hms/
     │       ├── controller/
     │       ├── model/
     │       ├── repository/
     │       ├── service/
     │       └── HospitalManagementSystemApplication.java
     └── resources/
         ├── static/
         ├── templates/
         └── application.properties


         thank you ❤️
         Made with ❤️ by Sadiq
