# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
# DATE:
### AIM:
# DATE:
To create a student database and execute DDL queries using SQL.

### DDL (Data Definition Language)
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
### List of DDL commands:
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers). DROP: This command is used to delete objects from the database. ALTER: This is used to alter the structure of the database. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed. RENAME: This is used to rename an object existing in the database.
## Query: ### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.
## SQL QUERY:
create table student(rollno int primary key, name varchar(20),age int,address varchar(100),phno varchar(10));
## OUTPUT:
![image](https://github.com/imthiyas19/F2_DBMS/assets/120353416/781d8138-cc0c-4f1c-bfa5-2a01dc79c1aa)
## 2) Change the above student table by adding another attribute department
## SQL QUERY:
alter table student add dept varchar(10);

## OUTPUT:
![image](https://github.com/imthiyas19/F2_DBMS/assets/120353416/580ccbd3-93c2-4902-9e60-a6653c2f00c8)
## 3) Drop the student table
## SQL QUERY:
drop table student;
## OUTPUT
![image](https://github.com/imthiyas19/F2_DBMS/assets/120353416/46174e45-e45b-46e5-a4a0-aad60b7de651)
### 4) Delete the student table using truncate keyword
## SQL QUERY:
truncate table student;

## OUTPUT:
![image](https://github.com/imthiyas19/F2_DBMS/assets/120353416/9a35e993-7498-4116-98c5-df30a2a146f9)
### 5) Rename the student table to mystudent
### SQL QUERY:
alter table student rename to mystudent;

### OUTPUT:
![image](https://github.com/imthiyas19/F2_DBMS/assets/120353416/f3675580-79ed-47a6-8f61-c9b8e3a53b33)
## RESULT:
Hence successfully created a student database and execute DDL queries using SQL.


