**History of SQL**: 
* In June 1970, Dr. E.F.Codd published the paper 'A Relational Model of Data for Large Shared Data Banks', which is now accepted as the definitive model for RDBMS and the language Structured English Query Language (SEQUEL) was developed by IBM Corporation Inc. to use Code's model.
* SEQUEL later became SQL. In 1979, Oracle Corporation introduces the first commercial RDBMS and today SQL is accepted as the Standard RDBMS language.


****

Definitions in SQL: 

* **Sql**: Its a query language that helps user to interact with the underlying relational database.
* **Database**: Its a collection of inter-related information
* **Information**: A processed data
* **Data**: Raw facts and figures that has no meaning
* **Relational Database**: This is a type of data storage method wherein the information will be stored in a series of tables that are connected through data relationships.
* **Relationships in Sql**: With the help of common fields/attributes of 2 tables, we establish an association between two or more tables. Often, the fields involves Primary and Foreign Keys.

***

**Logical Structure of Database**: The data in database part of secondary memory will get structured into Blocks, Extents, Segments and Table Spaces.

> Blocks: This is the smallest fragment of the memory where the data can be stored.

> Extents: The collection of blocks are called Extents

> Segments: The collection of extents.

> Table Spaces: The collection of Segments.

***

**Architecture of DBMS**: DBMS has a layered architecture and there are 3 layers/levels as listed below: 

1. **The Physical Layer**: This is the level that is close to the database.

2. **The Intermediate Layer**: This layer exists in between Physical layer and Logical layer.

3. **The User View/Logical Layer**: The layer that directly interacts with the user and will remain close to the user.

***

**Users of Database**
1. **End User**: The ultimate users of database who can view and access the data
2. **Database Designers**: DBD have privilege of defining and creating the database and the users who lets DBDs or authorizes DBDs to define and create the database are called DBAs.
3. **Database Administrators**: DBAs are sole custodian of entire database.
4. **Application Developers**: Developers are the users who build the front-end applications.



***
1. Types of Operators: 

a. **Arithmetic Operators**: These are the operators that we use in the Select Clause with the attributes. Ex. +, -, *, /

b. **Logical Operators**: We use Logical operators in the Where Clause to specify more than 1 condition. Ex. AND, OR, NOT

c. **Relational Operators**: The operators that compares the conditions and to be used in the Where Clause to specify the conditions. Ex. =,>,<>


1.a: **Order of Execution**: 
    1. Relational
    2. Logical 
    3. Arithmetic 
***


 Fragments of Secondary Storage: 
 > **File Storage**: In this part of secondary storage we can store any files that may or may not necessarily have a certain meaning and the user can access this storage without an intermediary. The search happens in this kind of storage is called Linear or Sequential.

 > **Database Storage**: Unlike the File Storage, the data that the user intends to store must have some meaning and all the data elements should be related to one another. The search happens in this storage is Binary Search.

***
Fragments of Database: 
 > **Data Part**: This is the part of database where the data values are stored
 
 > **Meta Data**: This part of the database maintains the data about the data. Meta Data aka Data Dictionary or Data Catalog.  

 ***

2. **Types of Functions in SQL**: Broadly speaking, there are 2 types of Functions. Single Row Functions and Multi-row functions 

a: Types of Single-row Functions in SQL: These functions are further classified into the below: 

a. Numeric/Arithmetic Functions: Accepts numeric input and returns numeric values. The following are the numeric functions: 

    1. Round: Rounds the value to specified decimal
        Syntax: Select Round(433.337,2)
        Result: 433.34
    2. Trunc: Truncates values to the specified decimal with no regard to rounding off
        Syntax: Trunc(433.337,2)
        Result: 433.33
    3. Mod: Retuens the reminder of division
        Syntax: Mod(1600,300)
        Result: 100
    4. ABS: Returns the absolute/positive value of a specified number
        Syntax: Select abs(-0.7)
        Result: .7
    5. Floor: Returns the largest integer value which is less than or equal to a number
        Syntax: Select Floor(21.53)
        Result: 21
    6. Ceiling: Returns the smallest integer value which is greater than or equal to a number specified
        Syntax: Select Ceiling(21.53)
        Result: 22

b. Aggregate Functions

    1. AVG 
    2. Count
    3. Min
    4. Max
    5. Sum

c. String Functions

    1. Character Converstion Functions: 
        A. Upper
        B. Lower
        C. Initcap
    2. Character Manipulation Functions: 
        A. Substr
        B. Instr
        C. Lpad
        D. Length
        E. Rpad
        F. Trim

d. Date Functions

    1. Datediff
    2. Current_Timestamp
    3. Months_between
    4. Next_day
    5. Last_day

e. Character Functions  



b: Multi-row Functions: Decode & Joins are popular Multi-row functions.

***