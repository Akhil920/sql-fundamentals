**History of SQL**: 
* In June 1970, Dr. E.F.Codd published the paper 'A Relational Model of Data for Large Shared Data Banks', which is now accepted as the definitive model for RDBMS and the language Structured English Query Language (SEQUEL) was developed by IBM Corporation Inc. to use Code's model.
* SEQUEL later became SQL. In 1979, Oracle Corporation introduces the first commercial RDBMS and today SQL is accepted as the Standard RDBMS language.


****

**Definitions in SQL**: 

* **Sql**: Its a query language that helps user to interact with the underlying relational database.
* **Database**: Its a collection of logically related information organized so that it can be  accessible, managed and updated easily. In general, Databases are accessed and controlled by a DBMS.
* **DBMS**: DBMS is an acronym for DataBase Management System. DBMS is a set of programs to store and access the data in an easy and efficient manner.
* **Information**: A processed data
* **Data**: Raw facts and figures that has no meaning
* **Relational Database**: This is a type of data storage method wherein the information will be stored in a series of tables that are connected through data relationships.
* **Relationships in Sql**: With the help of common fields/attributes of 2 tables, we establish an association between two or more tables. Often, the fields involves Primary and Foreign Keys.

***

**Need of DBMS**: 
> Database systems are basically developed for large amount of data. When dealing with huge amount of data, there are two things that require optimization: Storage of data and retrieval of data.
    1. **Storage** : As per the Database systems principles, the data should be stored in such a manner that it takes less space and while storing, we need to ensure that there should be no duplicates/redundant data, so in order to organize and store data in one place and creating links between these data, the need of DBMS arises.
    2. **Retrieval of Data**: Besides storing the data, DBMS also ensures that the data is retrieved as quickly as possible.

***


**Logical Structure of Database**: The data in database part of secondary memory will get structured into Blocks, Extents, Segments and Table Spaces.

> **Blocks**: This is the smallest fragment or unit of the memory where the data can be stored. In contrast, at the physical, operating system level, all the data is stored in bytes.

> **Extents**: An extent is a logical memory unit of database storage which is the collection of data blocks. DBA can also deallocate unused extents.

> **Segments**: A segment is the collection of extents that all are stored in the same tablespace.

> **Table Spaces**: The collection of Segments. A table space con contain tables, indexes, large objects and long data.

***

**Architecture of DBMS**: Database management systems architecture will help us understand the components of database system and the relation among them. DBMS has a layered architecture and there are 3 layers/levels as listed below: 

1. **The Physical Layer**: This is the level that is close to the database.

2. **The Intermediate Layer**: This layer exists in between Physical layer and Logical layer.

3. **The User View/Logical Layer**: The layer that directly interacts with the user and will remain close to the user.

***

**Users of Database**
1. **End User**: The ultimate users of database who can view and access the data
2. **Database Designers**: DBD have privilege of defining and creating the database and the users who lets DBDs or authorizes DBDs to define and create the database are called DBAs.
3. **Database Administrators**: DBAs are sole custodian of entire database who are resopnsible for managing the databases, including database security, access control, backup and disaster recovery.
4. **Application Developers or Software Developers**: Developers are the users who build the front-end applications.



***
1. **Types of Operators**: 

a. **Arithmetic Operators**: The arithmetic operators can perform arithmetical operation on numeric operands that are involved. These are the operators that we use in the Select Clause with the attributes. Ex. +, -, *, /

b. **Logical Operators**: We use Logical operators in the Where Clause to specify more than 1 condition. In other words, we use logical operators to specify conditions in teh SQL statement. Ex. AND, OR, NOT

c. **Relational Operators**: The operators that compares the conditions and to be used in the Where Clause to specify the conditions. This operator basically compares two expressions or values and return a boolean result. Ex. =,>,<>


1.a: **Order of Execution**: 
    1. Relational
    2. Logical 
    3. Arithmetic 
***


 Fragments of Secondary Storage: 
 > **File Storage**: In this part of secondary storage we can store any files that may or may not necessarily have a certain meaning and the user can access this storage without an intermediary. The search happens in this kind of storage is called Linear or Sequential.

 > **Database Storage**: Unlike the File Storage, the data that the user intends to store must have some meaning and all the data elements should be related to one another. The search happens in this storage is Binary Search.

***
Storage fragments of Database: 
 > **Data Part**: This is the part of database where the data values are stored
 
 > **Meta Data**: This part of the database maintains the data about the data. Meta Data aka Data Dictionary or Data Catalog.  

 ***
