1)Introduction
This project is designed to manage employee details, departments, roles, and attendance records using Oracle SQL. 
It provides an organized way for HR teams to track attendance, working hours, and employee performance.

2)Abstract

The Employee Management and Attendance Tracker project creates a relational database system with four main entities: Departments, Roles, Employees, and Attendance. It includes schema design, insertion of 200+ dummy records, and SQL queries to generate useful reports such as attendance summaries, late counts, and total working hours per employee. The project demonstrates the use of DDL, DML, joins, grouping, and aggregate functions in Oracle SQL.

3)Tools Used

Oracle SQL*Plus / SQL Developer – database and query execution
SQL – DDL (schema design), DML (insert, update, delete), joins, grouping, aggregate functions
SQL – for procedural logic and batch inserts (optional)

4)Schema Design

Departments → dept_id, dept_name
Roles → role_id, role_name
Employees → emp_id, emp_name, email, dept_id, role_id, hire_date
Attendance → att_id, emp_id, login_time, logout_time, status

4) Relationships:

Departments → Employees (dept_id)
Roles → Employees (role_id)
Employees → Attendance (emp_id)

5)Steps Involved

Designed schema with tables: Departments, Roles, Employees, Attendance.
Defined relationships using primary and foreign keys.
Inserted 100+ dummy records for employees and attendance.

