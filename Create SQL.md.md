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
