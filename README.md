📘 Section 3 – JDBC with Normalized Database
Overview

This section implements the Employee Payroll System using JDBC on a normalized MySQL database.
All database operations use PreparedStatement, JOIN queries, and are validated using JUnit 5.

Database Schema Used

Normalized tables:

employee

payroll

department

employee_department

The denormalized employee_payroll table is not used in this section.

Implemented Use Cases
UC-13: Read Employee Payroll Data (JOIN)

Retrieve employee and payroll details using JOIN

Commit: UC-13: Read employee payroll data using JOIN in JDBC

UC-14: Update Basic Pay

Update employee salary in payroll table

Commit: UC-14: Update employee basic pay using JDBC

UC-15: Retrieve Employees by Date Range

Filter employees by start date

Commit: UC-15: Retrieve employees by start date range

UC-16: Aggregate Salary by Gender

Calculate total salary by gender using JOIN

Commit: UC-16: Aggregate salary by gender using JOIN





Status

✅ Section 3 Completed and Verified