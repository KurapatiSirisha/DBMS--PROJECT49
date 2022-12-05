------------------------------------------------------------------------------------------
The file to have SQL statements to populate tables.
------------------------------------------------------------------------------------------
Database : Employee_manage
Table : tbl_Employee
Query:
INSERT INTO `employee_manage`.`tbl_employee` (`emp_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `emp_email`, `emp_pass`) VALUES ('111', 'Mouni', 'Roy', 'Female', '25', '4565458596', 'mouni@gmail.com', 'pass78');
SELECT `emp_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `emp_email`, `emp_pass` FROM `employee_manage`.`tbl_employee` WHERE  `emp_ID`=111;
/* #68: Access violation at address 0000000000717A78 in module 'heidisql.exe'. Read of address FFFFFFFFFFFFFFFF Message CharCode:13 Msg:256 */
INSERT INTO `employee_manage`.`tbl_employee` (`emp_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `emp_email`, `emp_pass`) VALUES ('112', 'Piter', 'Hog', 'Male', '30', '5465859675', 'hog@gmail.com', 'pass41');
SELECT `emp_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `emp_email`, `emp_pass` FROM `employee_manage`.`tbl_employee` WHERE  `emp_ID`=112;
/* #61: Access violation at address 0000000000717A78 in module 'heidisql.exe'. Read of address FFFFFFFFFFFFFFFF Message CharCode:13 Msg:256 */
INSERT INTO `employee_manage`.`tbl_employee` (`emp_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `emp_email`, `emp_pass`) VALUES ('113', 'JImmy', 'Hils', 'Male', '52', '6965457452', 'jimmy@gmai.com', 'pass54');
SELECT `emp_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `emp_email`, `emp_pass` FROM `employee_manage`.`tbl_employee` WHERE  `emp_ID`=113;
/* #15: Access violation at address 0000000000717A78 in module 'heidisql.exe'. Read of address FFFFFFFFFFFFFFFF Message CharCode:13 Msg:256 */
INSERT INTO `employee_manage`.`tbl_employee` (`emp_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `emp_email`, `emp_pass`) VALUES ('114', 'Kalyan', 'Karunaratne', 'Male', '35', '7845658541', 'kalyan@gmai.com', 'pass68');
SELECT `emp_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `emp_email`, `emp_pass` FROM `employee_manage`.`tbl_employee` WHERE  `emp_ID`=114;
*************************************************************************************************************************************************************************	
Table : tbl_Users
Query:
SELECT `admin_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `admin_email`, `admin_pass` FROM `employee_manage`.`tbl_users` WHERE  `admin_ID`=101;
INSERT INTO `employee_manage`.`tbl_users` (`admin_ID`, `fname`, `lname`, `gender`, `age`) VALUES ('102', 'Jone', 'Smith', 'Male', '25');
SELECT `admin_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `admin_email`, `admin_pass` FROM `employee_manage`.`tbl_users` WHERE  `admin_ID`=102;
UPDATE `employee_manage`.`tbl_users` SET `contact_address`='4152637485' WHERE  `admin_ID`=101;
SELECT `admin_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `admin_email`, `admin_pass` FROM `employee_manage`.`tbl_users` WHERE  `admin_ID`=101;
UPDATE `employee_manage`.`tbl_users` SET `contact_address`='4565987896', `admin_email`='jone@gmail.com' WHERE  `admin_ID`=102;
SELECT `admin_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `admin_email`, `admin_pass` FROM `employee_manage`.`tbl_users` WHERE  `admin_ID`=102;
UPDATE `employee_manage`.`tbl_users` SET `admin_pass`='pas234' WHERE  `admin_ID`=102;
SELECT `admin_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `admin_email`, `admin_pass` FROM `employee_manage`.`tbl_users` WHERE  `admin_ID`=102;
INSERT INTO `employee_manage`.`tbl_users` (`admin_ID`, `fname`, `lname`, `gender`, `age`) VALUES ('103', 'Jeson', 'ROy', 'Male', '22');
SELECT `admin_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `admin_email`, `admin_pass` FROM `employee_manage`.`tbl_users` WHERE  `admin_ID`=103;
UPDATE `employee_manage`.`tbl_users` SET `contact_address`='9639637478', `admin_email`='jeson@gmai.com', `admin_pass`='pass563' WHERE  `admin_ID`=103;
SELECT `admin_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `admin_email`, `admin_pass` FROM `employee_manage`.`tbl_users` WHERE  `admin_ID`=103;
INSERT INTO `employee_manage`.`tbl_users` (`admin_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `admin_email`, `admin_pass`) VALUES ('104', 'Monica', 'hill', 'Female', '23', '7898784563', 'monica@gmail.com', 'pass741');
SELECT `admin_ID`, `fname`, `lname`, `gender`, `age`, `contact_address`, `admin_email`, `admin_pass` FROM `employee_manage`.`tbl_users` WHERE  `admin_ID`=104;								
*************************************************************************************************************************************************************************	
Table : tbl_JobDepartment
Query:
INSERT INTO `employee_manage`.`tbl_jobdepartment` (`job_ID`, `job_dept`, `job_name`, `job_description`, `salary_range`) VALUES ('201', 'IT', 'IT', 'IT', '40000');
SELECT `job_ID`, `job_dept`, `job_name`, `job_description`, `salary_range` FROM `employee_manage`.`tbl_jobdepartment` WHERE  `job_ID`=201;
INSERT INTO `employee_manage`.`tbl_jobdepartment` (`job_ID`, `job_dept`, `job_name`, `job_description`, `salary_range`) VALUES ('202', 'IT', 'IT', 'IT', '50000');
SELECT `job_ID`, `job_dept`, `job_name`, `job_description`, `salary_range` FROM `employee_manage`.`tbl_jobdepartment` WHERE  `job_ID`=202;
INSERT INTO `employee_manage`.`tbl_jobdepartment` (`job_ID`, `job_dept`, `job_name`, `job_description`, `salary_range`) VALUES ('203', 'Management', 'HR', 'Management', '35000');
SELECT `job_ID`, `job_dept`, `job_name`, `job_description`, `salary_range` FROM `employee_manage`.`tbl_jobdepartment` WHERE  `job_ID`=203;
INSERT INTO `employee_manage`.`tbl_jobdepartment` (`job_ID`, `job_dept`, `job_name`, `job_description`, `salary_range`) VALUES ('204', 'CEO', 'CEO', 'CEO', '10000000');
SELECT `job_ID`, `job_dept`, `job_name`, `job_description`, `salary_range` FROM `employee_manage`.`tbl_jobdepartment` WHERE  `job_ID`=204;
*************************************************************************************************************************************************************************
