# Online Course Registration System (JavaFX & Database)

## Overview
This project is an Online Course Registration System developed using Java and JavaFX.
It provides a complete academic registration workflow with secure, role-based access for three different user types: Students, Instructors, and Administrators.

The system allows real-time interaction with a relational database to manage users, courses, and enrollments through a structured and modular architecture.
It focuses on advanced programming concepts, database integration, and GUI-based system design.

## User Roles and Permissions

### Student
- View available courses
- Register for courses
- Drop registered courses
- View personal schedule

### Instructor
- View assigned courses
- View enrolled students per course
- Update course availability

### Administrator
- Manage user accounts (add, update, delete)
- Manage course catalog
- Assign instructors to courses
- Control course availability
- View and manage all enrollments

## Features
- Role-based login system (Student / Instructor / Admin)
- Secure authentication and authorization
- Course registration and dropping functionality
- Real-time database interaction
- JavaFX graphical user interface
- Modular architecture using DAO pattern
- Custom exception handling for database and authentication errors

## Technologies Used
- Java
- JavaFX
- Scene Builder
- JDBC
- Relational Database (Oracle / MySQL-compatible design)
- Object-Oriented Programming (OOP)
- DAO Design Pattern

## System Architecture
- Model classes for core entities (User, Student, Professor, Course, Enrollment)
- DAO classes for database access and operations
- Controller classes for GUI logic
- FXML files for user interface design
- Centralized database connection management

## Project Structure
online-course-registration-system/
├── src/
│   ├── model/
│   ├── dao/
│   ├── controller/
│   └── util/
├── resources/
│   └── fxml/
└── README.md

## How to Run
1. Open the project in an IDE that supports JavaFX (IntelliJ IDEA or NetBeans recommended)
2. Ensure JavaFX is properly configured
3. Configure database connection settings in the DatabaseConnection class
4. Run the main application file
5. Log in using a valid user role

## Database Notes
- The system uses a relational database to store:
  - Users
  - Courses
  - Enrollments
- DAO classes handle all CRUD operations
- Database credentials and personal data should be replaced with placeholders before publishing publicly

## Learning Outcomes
- Building large-scale Java applications
- Integrating JavaFX with databases
- Applying MVC and DAO design patterns
- Implementing role-based access control
- Designing real-world academic systems

## Future Improvements
- Password encryption and hashing
- Enhanced input validation
- Reporting and analytics dashboard
- Deployment as a web-based system

## License
This project is developed for educational purposes only.
