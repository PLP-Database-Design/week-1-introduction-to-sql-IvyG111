1)State and Explain the components of a DBMS(Database Management System)

Database Engine
It executes queries, manages storage, and retrieves data efficiently.

Database Schema
Defines the structure of the database, including tables, fields, relationships, and constraints.
It ensures that data adheres to predefined formats and rules.

Query Processor
Interprets and executes SQL commands submitted by users or applications.
Optimizes query performance and retrieves requested data.

Transaction Manager
Ensures data integrity during concurrent operations.
Handles rollbacks and commits to maintain data consistency.

Database Manager
Manages storage space and allocates resources for data storage and retrieval.
Oversees indexing, data backups, and recovery processes.

User Interface
Allows users to interact with the DBMS through graphical tools or command-line interfaces.


2)What is a relational database? Give 4 examples.
A relational database is a structured database model where data is stored in tables . Each table consists of rows  and columns , with relationships established using keys.
Examples of Relational Databases
MySQL
PostgreSQL
Microsoft SQL Server
Oracle Database


3)State and Explain three classifications of SQL?
Data Definition Language (DDL)
Used to define and modify the structure of database objects such as tables and schemas.

Data Manipulation Language (DML)
Deals with inserting, updating, retrieving, and deleting data in the database.

Data Control Language (DCL)
Manages permissions and access control for users.


4)What is the difference between a Primary Key and a Foreign Key?
Primary Key uniquely identifies each record in a table.
Cannot contain null values and must be unique for all rows.

Foreign Key establishes a relationship between two tables by referencing the primary key of another table.
Ensures referential integrity.

5)What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram is a graphical representation of entities and their relationships within a database. It uses symbols such as rectangles for entities, diamonds for relationships, and ovals for attributes to illustrate the logical structure.



6)What are the advantages of relational databases?
Data Integrity
Ensures accuracy and consistency through constraints like primary keys and foreign keys.

Flexibility
Data can be easily queried and manipulated using SQL.

Scalability
Supports large-scale data storage and retrieval.


7)State four types of data type used to store data in tables?
Integer
Stores whole numbers. Example: Int, BIGINT.

String
Stores text data. Example: VARCHAR, CHAR.

Date/Time
Stores date and time values. Example: DATE, TIMESTAMP.

Boolean
Stores true/false values. Example: BOOLEAN.


8)What is the purpose of a database management system (DBMS)?
Efficient Data Storage and Retrieval
Organizes data systematically and ensures fast access.

Data Integrity and Security
Enforces rules and permissions to protect data from unauthorized access and corruption.

Concurrent Data Access
Allows multiple users to work with data simultaneously without conflicts.

Data Backup and Recovery
Ensures data is not lost due to hardware failures or other disruptions.