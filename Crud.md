------------------------------------------------------------------------------------------
A description of your database, including tables, attributes, primary
keys, foreign keys, foreign key constraints, FDs, whether in 3NF, and one or two rows of
sample data for each table.
------------------------------------------------------------------------------------------
Database : Employee_manage
Table : tbl_Employee
Table attribute:1. emp_ID PK
                2. fname
                3. lname
                4. gender
                5. age
                6. contact_address
                7. emp_email
                8. emp_pass
Table : tbl_Users
Table attribute:1. admin_ID PK
                2. fname
                3. lname
                4. gender
                5. age
                6. contact_address
                7. admin_email
                8. admin_pass
Table : tbl_JobDepartment
Table attribute:1. job_ID PK
                2. job_dept
                3. job_name
                4. job_description
                5. salary_range
Table : tbl_Salary_or_Bonus
Table attribute:1. salary_ID PK
                2. job_ID FK
                3. amount
                4. annual
                5. bonus
