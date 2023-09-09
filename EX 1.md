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
create table student(rollno numeric(10),name char(10),age numeric(5),address varchar(25),phoneno numeric(15));
### OUTPUT:
![create](https://github.com/Praveenanagaraji22/I2_DBMS/assets/119393514/05ce2ce4-0ba5-4b27-8dd0-682f5455cb7d)

### 2) Change the above student table by adding another attribute department
### SQL QUERY: 
alter table student add department varchar(15);
### OUTPUT:
![alter](https://github.com/Praveenanagaraji22/I2_DBMS/assets/119393514/c0eb14b2-3355-4a27-84a3-48f54ba61e43)


### 3) Drop the student table
### SQL QUERY: 
drop table student;
### OUTPUT:
![drop table](https://github.com/Praveenanagaraji22/I2_DBMS/assets/119393514/01e33494-3bf0-4512-a50c-4fdaabdae926)


### 4) Delete the student table using truncate keyword
### SQL QUERY: 
truncate table student;
### OUTPUT:
![delete](https://github.com/Praveenanagaraji22/I2_DBMS/assets/119393514/4b068dbc-9f0c-4e04-bf1a-93ff2fe3c1ff)



### 5) Rename the student table to mystudent
### SQL QUERY: 
rename table student to mystudent;
### OUTPUT:
![rename](https://github.com/Praveenanagaraji22/I2_DBMS/assets/119393514/18935c57-c66e-44bd-998c-f71154973e4e)
