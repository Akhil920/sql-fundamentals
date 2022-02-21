Before diving into the commands, we must be aware of few pointers that is common for all the SQL Commands. Such as: 
- All the Statements in SQL ends with semi-colon ";"
- Considering the presence of multiple DBMS environments, there will be a syntatical differences among these environments
- SQL queries are commonly used to create database objects and retrieving data from relational databases such as SQLSserver, MySQL, MariaDB and PostgreSQL
- SQL Command comprises of set of Statements, clauses, Predicates, expressions and values 
- There are many types of commands exist in SQL. For instance, DDL, DML, DCL, TCL, SCL, SSL etc.

***

SQL Commands are broadly divided into 4 categories: 
    1. Data Definition Language
    2. Data Manipulation Language
    3. Data Control Language
    4. Transaction Control Language

***

1. **Data Definition Language**: This is a subset of SQL statements that change the structure of the database schema in some way. These commands play an important role in the meta data part of the database. Moreover, while using these functions, we are required to specify the object type in the command. DDL is often referred to as auto-commit commands as well.

    a. ***Create Table Command***
        - Explanation: Create is a command that we use to create any Database Object. Examples of Database Objects are Table, Trigger, Clustter, Index etc. We can also specify column level constraints in the Create Command.
        - Syntax: Create <ObjectType> <ObjectName> (AttributeName, Datatype)... (AttributeNameN, Datatype/ColumnDefinition); 

2. 