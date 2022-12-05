------------------------------------------------------------------------------------------
The file to have SQL statements to create all tables.
------------------------------------------------------------------------------------------
Database : Employee_manage
Table : tbl_Employee
Query:
CREATE TABLE tbl_Users (admin_ID INT PRIMARY KEY AUTO_INCREMENT,
								fname VARCHAR(255) NOT NULL,
								lname VARCHAR(255) NOT NULL,
								gender ENUM('Male', 'Female', 'Others'),
								age INT NOT NULL,
								contact_address INT(11),
								admin_email VARCHAR (255),
								admin_pass VARCHAR(255)
								);
Table : tbl_Users
Query:
CREATE TABLE tbl_JobDepartment(job_ID INT PRIMARY KEY AUTO_INCREMENT,
										 job_dept VARCHAR(30) NOT NULL,
										 job_name VARCHAR(30) NOT NULL,
										 job_description VARCHAR(30) NOT NULL,
										 salary_range VARCHAR(30) NOT null
										 );
Table : tbl_JobDepartment
Query:
CREATE TABLE tbl_Salary_or_Bonus(salary_ID  INT(11) PRIMARY KEY,
											job_ID INT(11),
											amount INT(11),
											annual DATE,
											bonus DATE,
											FOREIGN KEY (job_ID) REFERENCES tbl_JobDepartment(job_ID)
											);
Table : tbl_Salary_or_Bonus
Query:
CREATE Table tbl_Qualification(qual_ID  INT(11) PRIMARY KEY,
								emp_ID INT(11),
								position VARCHAR(30) NOT NULL,
								requirements VARCHAR(30), 
								date_in DATE,
								FOREIGN KEY (emp_ID) REFERENCES tbl_Employee(emp_ID));
