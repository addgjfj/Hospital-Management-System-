# Hospital-Management-System-
A Hospital Management System project
About Dataset
This Hospital Management System project features a fully normalized relational database designed to manage hospital data including patients, doctors, appointments, diagnoses, medications, and billing. The schema applies database normalization (1NF, 2NF, 3NF) to reduce redundancy and maintain data integrity, providing an efficient, scalable structure for healthcare data management. Included are SQL scripts to create tables and insert sample data, making it a useful resource for learning practical database design and normalization in a healthcare context.

Usability
9.41

License
MIT

Expected update frequency
Never

Tags
Business
Hospitals and Treatment Centers
readme.md(1.79 kB)
About this file
Project description file

Hospital Management System
Project Description
This Hospital Management System is a relational database project designed to efficiently manage hospital data such as patients, doctors, appointments, diagnoses, medications, and billing. The system uses database normalization principles (1NF, 2NF, 3NF) to organize data into multiple related tables, minimizing redundancy and ensuring data integrity.

Key Features
Patient Management: Stores patient demographics and medical history.
Doctor Management: Maintains doctor profiles, including specialization and department.
Appointment Scheduling: Tracks patient appointments with doctors.
Diagnosis and Treatment: Records diagnoses linked to appointments and prescribed medications.
Billing Information: Manages billing details per appointment.
Normalized Database Design: Implements normalization for efficient data organization.
Technologies Used
Relational Database (MySQL, PostgreSQL, SQLite, or similar)
SQL for database design and queries
Dataset Structure
Patients: PatientID, Name, Age, Contact Info
Doctors: DoctorID, Name, Specialization, Department
Appointments: AppointmentID, PatientID, DoctorID, Date, DiagnosisID, BillAmount
Diagnoses: DiagnosisID, DiagnosisName, ICDCode
Medications: AppointmentID, MedicationName
How to Use
Clone the repository.
Set up the database using provided SQL scripts.
Run queries or integrate with your hospital management application.
Purpose
This project is designed to help understand and demonstrate practical database design and normalization techniques in a healthcare context.
