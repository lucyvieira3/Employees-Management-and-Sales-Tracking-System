# Employee Management and Sales Tracking System

In this SQL project, the goal was to design and implement a comprehensive Employee Management and Sales Tracking System for a fictional company with multiple branches. The project involved creating tables to organize and store employee records, personal information, sales records, and client data.

QUESTIONS TO ANSWER

1. Locate the onboarding information from all of the employees of this company. 
2. What client works with what branch? 
3. Who are all of the employees on payroll?
4. Who are the branch managers? 

HYPOTHESIS

1. Create an Employee records table for HR purposes.
   
<img width="1005" alt="Screenshot 2024-02-23 at 1 33 38 PM" src="https://github.com/lucyvieira3/Employees-Management-and-Sales-Tracking-System/assets/153330654/2cc95477-6bba-4cdd-852e-30b29f77e484">

2. Create a table to display the client and branch office relationship. Group by their branch ID.
   
<img width="271" alt="Screenshot 2024-02-23 at 1 33 56 PM" src="https://github.com/lucyvieira3/Employees-Management-and-Sales-Tracking-System/assets/153330654/41afc359-6dbd-47cc-9eec-76644f90360c">

3. Create a table to display all of the current employees on payroll. Group by their employee ID.
   
<img width="301" alt="Screenshot 2024-02-23 at 1 34 34 PM" src="https://github.com/lucyvieira3/Employees-Management-and-Sales-Tracking-System/assets/153330654/c793f894-09e6-4cad-920d-6f29e5b232b0">

4. Display each manager with their respective branch location.
   
   <img width="350" alt="Screenshot 2024-02-23 at 1 33 48 PM" src="https://github.com/lucyvieira3/Employees-Management-and-Sales-Tracking-System/assets/153330654/abf4b7c4-09ac-4aa5-86b7-1e3338ba161f">

APPROACH AND ANALYSIS 

1. I started this SQL script by creating each table as: employee, branch, client, works with and branch supplier.
2. I manually inserted the data of each employee and their clients on their respective tables.
3. The goal of this table was to easily locate important data from the company, so I proceeded with queries to find the following answers such as: the total employee count, average salary, branch managers per each branch, total sales per employee, and detailed client data.
4. I finished the project by answering gathering all of the previous information into organized tables and displayed as a dashboard in Tableau for HR purposes.

TECHNICAL CHALLENGES

Purposely for data exploration and problem solving purposes some of the data entered into the tables contain "NULL" values.

SUMMARY

<img width="1418" alt="Screenshot 2024-02-23 at 1 33 18 PM" src="https://github.com/lucyvieira3/Employees-Management-and-Sales-Tracking-System/assets/153330654/74d6733f-f52f-4c81-bed7-831eef15a36b">

Dashboard published on Tableau. 

SOFTWARE USED: Dbeaver - SQL, Tableau.

DATASET USED: Fictional Data

This Repository holds all of the code and queries from this project.
