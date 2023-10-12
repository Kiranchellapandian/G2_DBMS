# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

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
create table student(roll_no int,name varchar(25),age int,addresss
varchar(50),phone_no number(10));

### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/118668751/407a820b-e7ea-4623-b03d-2d6a8aa55df4)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
alter table student add department varchar(10);
### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/118668751/a9d1471f-3f56-47de-afd2-8b43cfe5d9da)



### 3) Drop the student table
 
### SQL QUERY: 
drop table mystudent;

### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/118668751/0a6a7e93-58d5-4465-a617-159630669470)



### 4) Delete the student table using truncate keyword

### SQL QUERY: 
truncate table student;

### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/118668751/84d456de-6a61-4c97-93c3-6cba9696c71c)



### 5) Rename the student table to mystudent

### SQL QUERY: 
alter table student rename to mystudent;

### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/118668751/82ff6368-b660-46f8-8d8d-e24631dec0a2)


