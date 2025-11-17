PL/SQL Collections, Records & GOTO Demonstration

Student Name: BAHATI Arsene

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
