# sql-challenge



## Database Diagram screenshot and code


![Diagram consturcted in QuickDBD](EmployeeSQL/DatabaseDiagram.png)

departments
-
dept_no VARCHAR PK
dept_name VARCHAR

dept_emp
-
emp_no INT PK FK >- employees.emp_no
dept_no VARCHAR PK FK >- departments.dept_no

dept_manager
-
dept_no VARCHAR PK FK >- departments.dept_no
emp_no INT PK FK >- employees.emp_no

employees
-
emp_no INT PK
emp_title_id VARCHAR FK >- titles.title_id
birth_date DATE
first_name VARCHAR
last_name VARCHAR
sex VARCHAR
hire_date DATE

salaries
-
emp_no INT PK FK >- employees.emp_no
salary INT

titles
-
title_id VARCHAR PK
title VARCHAR


## Query Table Schemata

*This code was imported into pgAdmin 4 from QuickDBD, located in the EmployeeSQL folder in the SQL Source File labelled SQL.diagram.schemata*



## Query Code
*Located in the EmployeeSQL folder in the SQL Source File labelled SQL.employee.queries*


## Query Results

![Query 1 result](EmployeeSQL/resultsscreenshot/query1.png)
![Query 2 result](EmployeeSQL/resultsscreenshot/query2.png)
![Query 3 result](EmployeeSQL/resultsscreenshot/query3.png)
![Query 4 result](EmployeeSQL/resultsscreenshot/query4.png)
![Query 5 result](EmployeeSQL/resultsscreenshot/query5.png)
![Query 6 result](EmployeeSQL/resultsscreenshot/query6.png)
![Query 7 result](EmployeeSQL/resultsscreenshot/query7.png)
![Query 8 result](EmployeeSQL/resultsscreenshot/query8.png)





