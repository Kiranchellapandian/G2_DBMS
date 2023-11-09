# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## DATE:
## AIM:
To create a student database and execute DDL queries using SQL.

## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.
### SQL QUERY: 
```create table student(roll_no int,name varchar(25),age int,addresss varchar(50),phone_no number(10));```
### OUTPUT:
![image](https://github.com/NIXANDASS/I2_DBMS/assets/118781418/c4d46081-2e59-4aca-b120-5f34bdd1a520)
### 2) Change the above student table by adding another attribute department
### SQL QUERY: 
#### ``` alter table student add department varchar(10);```
### OUTPUT:
![image](https://github.com/NIXANDASS/I2_DBMS/assets/118781418/dc097929-58dd-4a57-b932-f6b82574c29f)
### 3) Drop the student table
### SQL QUERY:
#### ```drop table mystudent;```
### OUTPUT:
![image](https://github.com/NIXANDASS/I2_DBMS/assets/118781418/8d425077-2acf-48a6-85f2-a1a195d3dc7e)
### 4) Delete the student table using truncate keyword
### SQL QUERY: 
#### ```truncate table student;```
### OUTPUT:
![image](https://github.com/NIXANDASS/I2_DBMS/assets/118781418/f6b5b7c2-55e5-4514-90b9-361a055113e4)
### 5) Rename the student table to mystudent
### SQL QUERY: 
#### ```alter table student rename to mystudent;```
### OUTPUT:
![image](https://github.com/NIXANDASS/I2_DBMS/assets/118781418/7361aaf2-6e6a-4e1b-8de1-f7584fdb1056)
### RESULT:
A student database was created and DDL commands were executed using SQL.
