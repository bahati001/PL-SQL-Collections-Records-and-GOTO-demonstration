PL/SQL Collections, Records & GOTO Demonstration

Student Name: CYIZERE SIBORUREMA Elie
Course: INSY 831 – Database Development with PL/SQL
Instructor: Eric Maniraguha
Date: November 2025

🎯 Project Purpose

This project illustrates how PL/SQL supports composite data handling through Collections, Records, and controlled flow using the GOTO statement.
A simplified payroll and personnel scenario is used to demonstrate these features clearly and practically.

📘 What This Project Covers
Concept	PL/SQL Element	What It Demonstrates
Associative Array	city_population	Maintains population values keyed by city name
VARRAY	salary_varray_t	Holds up to five salary figures for an employee
Nested Table	bonus_nt_t	Stores a flexible list of bonuses that can have deleted / missing positions
Table-Based Record	%ROWTYPE	Retrieves a full row from the employees table
User-Defined Record	emp_rec_t	Combines multiple fields including a VARRAY of salary data
Cursor-Based Record	c_emp cursor	Used to loop through several employee rows
GOTO	retry_label, exit_label	Shows how PL/SQL can jump between labeled sections when needed
Collection of Records	employees_tab	Holds multiple employee records using an associative array
⚙️ Running the Demo
1️⃣ Enable DBMS Output

Before running the script, turn on output in SQL Developer / SQL*Plus:

SET SERVEROUTPUT ON;

2️⃣ Execute the PL/SQL Block

Run the demo package or anonymous block provided in the project.

3️⃣ Review the Printed Output

The program prints labeled sections showing:

City populations

Salary VARRAY entries

Bonus Nested Table values

Cursor-based employee rows

Record contents

GOTO flow control behavior

📝 Notes

The demonstration focuses only on the features listed above.

All examples include comments for clarity.

The GOTO usage is intentionally small and controlled, as required by the instructor.
