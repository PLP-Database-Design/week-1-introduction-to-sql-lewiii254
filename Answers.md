1. Components of DBMS
  a) hardware: a physical device to operate the database hence including servers, storage devices and networking equipments that store and process the database eg harddrive
  b)Software: a DBMS SOFTWARE And other supporting software such as an operating software. handles all operations like data storage, retrival and updating And also security of data. eg. MYSQL,PostgreSQL, MongoDB
  C)Data: collection of raw facts and figures stored in the database eg. customer information
  d)Users: people interacting with the DBMS 
  E)DATABASE Access language: query language eg SQL allow users to interact with the database

2. A relational Database is like a big table where you store information in rows and columns and the data in different can be connected to each other. It helps keep things organized so you can find and use the information easily.
Examples include: 
- MySQL
- PostgreSQL
- SQLite 
- Microsoft SQL Server

3. Classfications of SQL
- Data Definition Language (DDL)
  * defines and manages the structure of a database. its key commands are  CREATE - makes new tables or databases, ALTER - changes the structure of a tabe, DROP - deletes tables or databases
- Data Manipulation Langauge (DML)
  * Handles the data stored in a database (inserting, updating, or deleting records) . Common Commands are INSERT - Adds new data to a table, UPDATE -Changes exixsting data, DELETE: Removes data from a table
- Data Query language (DQL)
  * Retrieves data from a database . Common command is SELECT: Used to fetch data on conditions

4. A primary key is a special column in a table that uniquely identifies each row (Unique ID for every entry)
   A Foreign key is a column in one table that connects to the Primary key  in another table . It links the two tables together.

5. An Entity Relationship Diagram is a visual representation of how different entities in a database are related to each other. It shows the structure of the database and how tables are  connected
* key parts are:
-  Entities- objects or things you store data about
-  Attributes - Detais or characteristics of an entity
-  Relationships - shows how entities are related

6. Advantages of relational databases
* Data integrity and Accuracy: it ensures the data is accurate and consistent through rules like primary and foreign keys
* Easy to organize and Query data : data is stored in rows and columns hence easy to organize and search using SQL queries
* Scalability and  Flexibility : They can handle large amounts of data and scale as your needs grow
* Data Security : they provide robust security features like user permissions, 
* Backup and Recovery : they provide strong back up and recovery options ensuring data safety in case of failure.

7. Types of data used to store data in tables
 * INT (integer) - store whole numbers
 * VARCHAR (Variable Character) - stores text or string values of variable length
 * DATE - stores date values (year, month, day)
 * TEXT - Stores large amounts of text or string data (larger than VARCHAR)

 8. The Purpose of a **Database management system** is to efficiently and securely manage, store, retrieve, and manipulate data in databases:
    1. Data storage and management - Helps store data  in an organized manner.
    2. Data integrity and Security - ensures data is accurate,and protected from unauthorized access
    3. lets you find information quickly - you can easily search for a specific information
    4. shares information - you can let others see and use your information, if you want

