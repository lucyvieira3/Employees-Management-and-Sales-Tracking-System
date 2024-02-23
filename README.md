# Employee Management and Sales Tracking System

In this SQL project, the goal was to design and implement a comprehensive Employee Management and Sales Tracking System for a fictional company with multiple branches. The project involved creating tables to organize and store employee records, personal information, sales records, and client data.

QUESTIONS TO ANSWER

1. Retrieve onboarding information for all employees within the organization.
2. Determine the client assignments corresponding to each branch.
3. Compile a comprehensive list of all employees currently on the payroll.
4. Identify individuals holding the position of branch manager across the company.

HYPOTHESIS

1. Establish an Employee Records Table to serve the specific needs of HR.
   
<img width="1005" alt="Screenshot 2024-02-23 at 1 33 38 PM" src="https://github.com/lucyvieira3/Employees-Management-and-Sales-Tracking-System/assets/153330654/2cc95477-6bba-4cdd-852e-30b29f77e484">

2. Establish a table to depict the relationship between clients and branch offices, organized by their respective branch IDs.
   
<img width="271" alt="Screenshot 2024-02-23 at 1 33 56 PM" src="https://github.com/lucyvieira3/Employees-Management-and-Sales-Tracking-System/assets/153330654/41afc359-6dbd-47cc-9eec-76644f90360c">

3. Establish a table to present a comprehensive roster of the current employees on the payroll, organized and grouped according to their employee IDs.
   
<img width="301" alt="Screenshot 2024-02-23 at 1 34 34 PM" src="https://github.com/lucyvieira3/Employees-Management-and-Sales-Tracking-System/assets/153330654/c793f894-09e6-4cad-920d-6f29e5b232b0">

4. Present a comprehensive display showcasing each manager alongside their corresponding branch location.
   
   <img width="350" alt="Screenshot 2024-02-23 at 1 33 48 PM" src="https://github.com/lucyvieira3/Employees-Management-and-Sales-Tracking-System/assets/153330654/abf4b7c4-09ac-4aa5-86b7-1e3338ba161f">

APPROACH AND ANALYSIS 

1. The initiation of this SQL script involved the creation of distinct tables, namely employee, branch, client, works with, and branch supplier.
2. The subsequent step encompassed the manual insertion of data pertaining to each employee and their corresponding clients into the respective tables.
3. The primary objective of this project was to facilitate the streamlined retrieval of critical company data. Consequently, queries were executed to ascertain key metrics, including total employee count, average salary, branch managers for each branch, total sales per employee, and comprehensive client information.
4. The culmination of this process involved the consolidation of the gathered information into meticulously organized workbooks. The newly compiled CSV data was exported to Tableau. Within Tableau, a relational structure was established between the various employee tables, culminating in the creation of a final dashboard tailored for HR purposes.

TECHNICAL CHALLENGES

Intentionally, for the purposes of data exploration and problem-solving, certain entries within the tables have been designated with "NULL" values.

SUMMARY

<img width="1418" alt="Screenshot 2024-02-23 at 1 33 18 PM" src="https://github.com/lucyvieira3/Employees-Management-and-Sales-Tracking-System/assets/153330654/74d6733f-f52f-4c81-bed7-831eef15a36b">

Dashboard published on Tableau. 

SOFTWARE USED: Dbeaver - SQL, Tableau.

DATASET USED: Fictional Data

This Repository holds all of the code and queries from this project.
