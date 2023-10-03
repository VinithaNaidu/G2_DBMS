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
CREATE TABLE student_1 (rollno numeric,name varchar(20),age numeric,address varchar(40),phno numeric);

### OUTPUT 
![image](https://github.com/VinithaNaidu/G2_DBMS/assets/121166004/9a0aed63-ec41-4630-ac0f-19360208c034)




### 2) Change the above student table by adding another attribute department

### SQL QUERY : 
ALTER TABLE student_1 ADD dept varchar(15);

### OUTPUT:
![image](https://github.com/VinithaNaidu/G2_DBMS/assets/121166004/b2ee1a64-d5ed-4647-910a-d4cfa4c707d6)


### 3) Drop the student table
 
### SQL QUERY: 
DROP TABLE mystudent;


### OUTPUT:
![image](https://github.com/VinithaNaidu/G2_DBMS/assets/121166004/fe7be413-291d-4eca-8884-e358aebb029e)



### 4) Delete the student table using truncate keyword

### SQL QUERY:
TRUNCATE TABLE student_1;


### OUTPUT:

![image](https://github.com/VinithaNaidu/G2_DBMS/assets/121166004/5be3ad48-9ed2-4f1f-95d1-b0903197ccdb)



### 5) Rename the student table to mystudent

### SQL QUERY:
ALTER TABLE student RENAME TO mystudent;


### OUTPUT:
![image](https://github.com/VinithaNaidu/G2_DBMS/assets/121166004/bc7af4ec-b575-4b83-bd2b-79efe81604c0)

