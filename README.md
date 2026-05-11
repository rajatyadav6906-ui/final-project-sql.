# University Database Management System
This project is a comprehensive SQL-based system designed to manage academic data. It focuses on the relationships between students, faculty, and coursework, providing a structured way to store and analyze university operations.

# Database Structure & Logic
The project is built around five core tables, each designed to handle a specific part of the university ecosystem:

Departments: The structural foundation (e.g., Computer Science, Mathematics).

Students: A detailed registry containing personal profiles and enrollment history.

Courses: An academic catalog that links specific subjects to their respective departments and credit values.

Instructors: A management table for faculty details, including departmental ties and payroll (salary) tracking.

Enrollments: The bridge table that connects students to their chosen courses, enabling the tracking of academic progress.

# Advanced Features & Operations
## 1. Comprehensive Data Management (CRUD)
The script provides a full roadmap for managing data:

Create: Methods to add new records to any table.

Read: Techniques to retrieve and view data clearly.

Update: Scripts to modify existing information, such as updating department names or student emails.

Delete: Procedures to remove data without breaking the links between tables.

## 2. Complex Data Analysis
Beyond simple storage, this project uses advanced SQL to answer difficult questions:

Automated Labeling: Uses logic to categorize students as "Senior" or "Junior" based on their enrollment date relative to the current year.

Enrollment Insights: Identifies students who are taking specific difficult combinations (like taking both "SQL" and "Data Structures" simultaneously).

Financial Tracking: Calculates department-level salary peaks and average credit loads across the curriculum.

Window Functions: Uses professional-grade SQL to calculate "Running Totals" for student enrollments.

# Technical Tools Used
Relational Joins: Using INNER JOIN and LEFT JOIN to merge data from multiple tables into a single view.

Constraints: Implementing PRIMARY KEY, FOREIGN KEY, and CHECK constraints to ensure data accuracy (e.g., preventing negative salaries).

Aggregation: Mastering GROUP BY and HAVING clauses to filter summarized data.

Subqueries: Using "queries within queries" to find specific groups of students based on course popularity.

