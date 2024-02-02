<<<<<<< HEAD
# University-Grad-System
=======
# Postgrad System

Welcome to the Postgrad System project repository! This project aims to create a comprehensive platform for managing postgraduate programs, including student registration, thesis tracking, progress reporting, course management, and publication tracking. The system caters to administrators, supervisors, and students, providing them with the necessary tools to streamline and automate various processes involved in postgraduate studies at the German University in Cairo (GUC).

## System Requirements

### Users

The Postgrad System accommodates different types of users:

#### Admin
- The admin has full control over the system and can update details as needed.

#### Student
- Students can be either non-GUCians or GUCians.
- Required student information includes name, email, type (Master or PhD), GPA, address, faculty, and mobile number(s).
- GUCian students also have an undergraduate ID.
- After registration, each student receives a unique numeric ID.
- Students can progress from a Master's degree to a PhD, with the system tracking their theses in both cases.

#### Supervisor
- Supervisors oversee students during their thesis work.
- Required supervisor information includes name, faculty, ID, and email.
- Supervisors can view and evaluate their students' progress reports.

### Thesis

- Each thesis has a unique serial number, title, type (Master or PhD), field, start date, end date, seminar date, and number of extensions needed.
- The system calculates the duration spent on each thesis since the start date.
- Theses have associated payments and defenses.

### Defense

- Defenses include a date, grade, and location.
- Examiners attend defenses to evaluate and provide comments.
- Examiners have names, fields of work, and can be national or international.

### Progress Report

- Students submit progress reports for their theses, including progress state, description, date, and evaluation.

### Course

- Non-GUCian students must take courses, each with a unique ID, code, credit hours, and associated fee.
- The system tracks student grades in courses.

### Publication

- Students can publish publications with details such as posting date, title, host (conference name), and place (conference location).
- Publications are associated with one or more theses and can be tracked for acceptance.

### Payment

- The system tracks total amounts, fund percentages, installment numbers, and payment IDs for fees and publications.
- Payments can be divided into installments, each with a date, amount, and status (paid or not).

## Development Process

1. **Entity-Relationship Diagram (ERD)**: Initially, an ERD diagram was created to design the database schema and establish table relations.

2. **Database Creation**: Based on the ERD diagram, the database schema was created, including table structures and relationships.

3. **SQL Functions and Stored Procedures**: Required SQL functions and stored procedures were developed to implement various functionalities, such as data retrieval, manipulation, and processing.

4. **Website Development**: The web-based interface for the Postgrad System was implemented using ASP.NET, incorporating the database schema, functions, and procedures to create a user-friendly and efficient platform.

## Conclusion

The Postgrad System project aims to enhance the management of postgraduate programs at GUC, providing a user-friendly and efficient platform for administrators, supervisors, and students. With its comprehensive features and robust functionality, the system aims to streamline processes and improve overall efficiency in postgraduate studies.

Thank you for your interest in the Postgrad System project. For any inquiries or assistance, please reach out to the project maintainers. Happy coding! 🎓💻
>>>>>>> origin/main
