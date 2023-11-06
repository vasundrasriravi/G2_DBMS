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
```
 create table student(rollno int,name char(20),age int,address varchar(20),phoneno int);
```
### OUTPUT:
![table](https://github.com/vasundrasriravi/G2_DBMS/assets/119393983/4b671aff-76ab-4668-8cc7-3ac754aaeaf2)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);
```
### OUTPUT:
![alter](https://github.com/vasundrasriravi/G2_DBMS/assets/119393983/d91621e4-2181-4aa2-b981-5f03e5857674)

### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;
```
### OUTPUT:
![drop](https://github.com/vasundrasriravi/G2_DBMS/assets/119393983/ab06d9df-f122-49a4-8ef7-0001bab942ae)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```
### OUTPUT:
![t1](https://github.com/vasundrasriravi/G2_DBMS/assets/119393983/b13743e1-b336-4d69-9806-25f82c1ef876)

### 5) Rename the student table to mystudent

### SQL QUERY: 
```
alter table student rename to mystudent;
```
### OUTPUT:
![rename](https://github.com/vasundrasriravi/G2_DBMS/assets/119393983/f2a4eeeb-6e61-4ba6-92d5-9d01e454c0fd)

### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
