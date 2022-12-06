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
