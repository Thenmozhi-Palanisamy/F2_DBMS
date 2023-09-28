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
```
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
```


### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/F2_DBMS/assets/95198708/5cc61ca0-64a9-471e-9f20-5aab45f2ae91)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);
```

### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/F2_DBMS/assets/95198708/e9f39445-b222-4e8f-95aa-4d7c0023cd69)



### 3) Drop the student table
 
### SQL QUERY: 
```

drop table student;
```
### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/F2_DBMS/assets/95198708/a7bbf8c3-edb8-4c94-88c2-f16e78cbb3f4)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;



```


### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/F2_DBMS/assets/95198708/8f5afdd0-4e69-4824-bcf5-274936ea8499)




### 5) Rename the student table to mystudent

### SQL QUERY: 

```
alter table student rename to mystudent;
```

### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/F2_DBMS/assets/95198708/186d1c37-d3a5-4445-acb9-721c8c76a4dc)

## Result:

To create a student database and execute DDL queries using SQL is executed successfully.
