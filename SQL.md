# MYSQL TUTORIAL

Important Terminologies

1. What is Data?

>Collection of unprocessed is known as data.

2. What is database?

>Collection of related data is known as a database.

3. What is DBMS(Database Management System)?

>Database which containing interrelated data along with a set if application programs to manage the data stored in database is known as database management system. 

4. What is RDBMS(Relational Database Management System)?
>A database management system is known as relational Database management system if the database is stored in form of tables. Tables are also known as relations. it consists of Rows and Columns Like RDBMS also has a set of application programs to access the database
Ex- Oracle, Mysql, Postsql etc.


## Data Types -



## Sub Language of SQL

### 1. DDL(Data Description/Defination Language)
>This language is used to create and destroy the database objects. Generally, database  admininstrator use this sublangauage to create or change the structure of a database.
### 2. DML(Data Manipulation Language)
>After the database is created it necessary to insert retrives and modify the data contained within the database . So DML is a language which helps us to do the above operations.
### 3. DCL(Data Control Language)
>Some controls Statements are necessary to control the transactions in database. 

>DCL sublanguage is going to help us to do so.
#### 1. Commit Statement :
> To make the change permanent for the current transaction.

#### 2. Rollback Statement :
> To undo all the changes for current transactions

### 4. DRL(Data Retrieval Language)
>DRL language is an SQL Language which helps us to retrieve data from the database. Example , SELECT commands.

# Querries

1. Create Database
 ```sql
 CREATE DATABASE database_name;
 ```
 2. Drop Database
```sql
DROP database_name;
```
3. Create Table with multiple columns
```sql
CREATE TABLE table_name(column_name datatype(size), column_name datatype(size), column_name datatype(size), column_name datatype(size), column_name datatype(size) ,primary key(column_name));
```
4 Describe table 
```sql
DESC table_name;
```
5. Add Column in table
```sql
ALTER TABLE table_name
ADD column_name datatype(size) NOT NULL;
```

6. Add multiple Column in table
```sql
ALTER TABLE table_name
ADD column_name datatype(size),
ADD column_name datatype(size)
;
```
