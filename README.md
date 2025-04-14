# Project
The Hospital Management System (HMS) is a Java-based application designed to manage various operations in a hospital environment. The system allows the hospital to manage patients, doctors, and appointments. The project connects to a PostgreSQL database to store and retrieve data, offering a simple interface for administrators to interact with the hospital's data.
# Features
* Add Patients: The system allows adding new patients by entering their name, age, and gender.

* View Patients: A simple interface to view all patients and their details.

* View Doctors: List of all available doctors along with their specializations.

* Book Appointments: Allows booking appointments for patients with available doctors on a specified date, ensuring the doctor is not double-booked.

* Database Integration: The system interacts with a PostgreSQL database to store all records related to patients, doctors, and appointments.
# Programming Language: Java

# Database: PostgreSQL

# JDBC: For database connectivity

# Example Workflow:
Add a patient by providing their name, age, and gender.
View the list of all patients.
View available doctors with their specializations.
Book an appointment by providing patient ID, doctor ID, and appointment date.

# Error Handling
The system checks for invalid data such as incorrect date formats when booking appointments.
If an appointment date is already taken by another patient for the same doctor, the system will notify the user and prevent the booking.



