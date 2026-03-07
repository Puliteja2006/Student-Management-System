# Student Management System

A Java console-based application that manages student records using JDBC and MySQL.
This project demonstrates backend development concepts such as database connectivity, CRUD operations, and structured Java application design.


## Features:

- Add new student records
- View all students in the system
- Search students by ID
- Delete student records
- Console-based interactive menu
- Persistent data storage using MySQL database
  

## Technologies Used:

- Java
- JDBC (Java Database Connectivity)
- MySQL
- NetBeans IDE


## Project Structure:

StudentManagementSystem
│
├── src
│ └── studentmanagements
│ ├── Student.java
│ ├── StudentManager.java
│ ├── DatabaseConnection.java
│ └── StudentApp.java
│
├── build.xml
├── manifest.mf
└── database.sql


## Database Schema:

CREATE DATABASE student_management;

USE student_management;

CREATE TABLE students (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    email VARCHAR(100),
    course VARCHAR(50),
    age INT
);


## How to Run the Project:

1. Clone the repository
2. Import the project into NetBeans / IntelliJ IDEA
3. Create the database in MySQL using the provided SQL script
4. Update database credentials in "DatabaseConnection.java"
5. Run "StudentApp.java"


## Example Console Output:

----- Student Management System -----

1. Add Student
2. View Students
3. Search Student
4. Delete Student
5. Exit


## Future Improvements:

- Add Update Student feature
- Build GUI version using Java Swing / JavaFX
- Convert project to Spring Boot REST API
- Add authentication and role-based access


## Author:

Puli Sai Srinivasa Teja
Aspiring Java Backend Developer
Focused on building real-world backend applications using Java, JDBC, MySQL, and Spring Boot.
