# DBMS--PROJECT49
o the link to our project repo-https://github.com/KurapatiSirisha/DBMS--PROJECT49
o member’s GitHub IDs and names- 
KurapatiSirisha- Sirisha Kurapati
Rakeshkore- Rakesh kore
ravipatidivya- Ravipati Divya
vams5- Vamsi Gaddam 
o the link to our project’s demo video 
------------------------------------------------------------------------------------------
Database Requirements
------------------------------------------------------------------------------------------
-The database should have 4 tables.
    tbl_Employee
    tbl_Users
    tbl_JobDepartment
    tbl_Salary_or_Bonus
- Each table should have at least 4 fields (including primary keys)
    tbl_Employee
        -emp_ID PK
    tbl_Users
        -admin_ID PK
    tbl_JobDepartment
        -job_ID PK
    tbl_Salary_or_Bonus
        -salary_ID PK
- Also please specify triggers and policies on foreign key
tbl_Employee
        -emp_ID PK
        -fname
        -lname
        -gender
        -age
        -contact_address
        -emp_email
        -emp_pass
    tbl_Users
        -admin_ID PK
        -fname
        -lname
        -gender
        -age
        -contact_address
        -admin_email
        -admin_pass
    tbl_JobDepartment
        -job_ID PK
        -job_dept
        -job_name
        -job_description
        -salary_range
    tbl_Salary_or_Bonus
        -salary_ID PK
        -job_ID FK
        -amount
        -annual
        -bonus
