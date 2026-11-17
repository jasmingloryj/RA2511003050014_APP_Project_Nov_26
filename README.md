# Hospital Appointment and Queue Management System

## Course Details

- Course ID: 21CSC203P
- Course Name: Advanced Programming Practice
- Academic Year: 2026–2027
- Department: Computer Science and Engineering

## Team Members

| Name | Register Number | Department | Section | Academic Year |
|---|---|---|---|---|
| S Samiksha | RA2511003050014 | CSE | II CSE A | 2026-27 |
| Jasmin Glory J | RA2511003050016 | CSE | II CSE A | 2026-27 |
| Akshadha Arunkumar | RA2511003050025 | CSE | II CSE A | 2026-27 |
| Pooja PL | RA2511003050027 | CSE | II CSE A | 2026-27 |

## Project Mentor
Dr. S. SHARGUNAM

Assistant Professor, Department of Computer Science and Engineering

## Project Overview
The Hospital Appointment and Queue Management System is a Java-based desktop application developed to simplify hospital appointment scheduling and patient queue management. It provides separate access for patients, doctors and administrators.

The system enables patients to book appointments and submit emergency requests, while doctors can manage patient queues, review emergency requests and record consultations. It aims to improve patient flow through organized queue management and doctor-controlled emergency prioritization.

## Technologies Used
- Java
- Java Swing
- MySQL
- JDBC
- MySQL Connector/J

## Key Features

- Patient registration and authentication
- Role-based access for Patients, Doctors, and Admins
- Appointment booking, rescheduling, and cancellation
- Automatic queue generation
- Priority-based queue management
- Emergency request submission and doctor approval
- Doctor consultation management
- Prescription management
- Patient medical records
- Doctor and department administration

## Database
Database name: "hospital_queue_v2"

The database contains eight tables:
1. "users"
2. "patients"
3. "doctors"
4. "departments"
5. "appointments"
6. "queue"
7. "consultations"
8. "prescription_items"

The SQL export is available in the "database" folder.

## Project Structure
- "SRC/" – Java source code
- "LIB/" – Required libraries
- "database/" – SQL database export
- "screenshots/" – Application screenshots

## Setup Instructions
1. Install Java JDK and MySQL.
2. Import "database/database_final.sql" into MySQL.
3. Configure the database connection in the project.
4. Ensure MySQL Connector/J is available in the "LIB" folder.
5. Open the project in a Java IDE.
6. Run the application's main class.

## User Roles
- Patient: Book appointments, view queue status, and submit emergency requests.
- Doctor: Manage queues, review emergency requests, conduct consultations, and prescribe medicines.
- Admin: Manage doctors and departments.

## Project Purpose
Developed as an academic project to demonstrate Object-Oriented Programming, Java GUI development, database connectivity, and transaction-based data management.
