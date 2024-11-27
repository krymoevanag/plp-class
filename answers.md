
# Database Management System (DBMS) Questions and Answers

## Components of a DBMS (Database Management System)
1. **Database Engine**  
   - Responsible for data storage, retrieval, and processing. It uses algorithms to perform CRUD (Create, Read, Update, Delete) operations efficiently.  
   
2. **Database Schema**  
   - Defines the structure, format, and organization of data, including tables, columns, data types, and relationships.  

3. **Query Processor**  
   - Interprets and executes database queries, typically written in SQL, and converts them into actions that the DBMS engine can perform.  

4. **Transaction Management**  
   - Ensures database integrity and consistency by managing transactions, supporting features like rollback, commit, and ACID properties.  

5. **Data Storage Management**  
   - Handles how data is stored on physical media, optimizing storage space and access speed.  

6. **Database Security**  
   - Provides mechanisms for data protection, including user authentication, role-based access control, and encryption.  

7. **Concurrency Control**  
   - Manages simultaneous database access by multiple users to prevent conflicts or inconsistencies.  

8. **Backup and Recovery System**  
   - Ensures data safety by providing features for regular backups and restoring the database in case of failures.  

---

## What is a Relational Database? 
A **relational database** stores data in structured tables (rows and columns), where relationships between data are established using keys. It uses SQL for query operations. 

**Examples**:  
1. MySQL  
2. PostgreSQL  
3. Oracle Database  
4. Microsoft SQL Server  

---

## Three Classifications of SQL
1. **Data Definition Language (DDL)**  
   - Used to define or modify database structures.  
   - Examples: `CREATE`, `ALTER`, `DROP`, `TRUNCATE`.  

2. **Data Manipulation Language (DML)**  
   - Handles data manipulation within tables.  
   - Examples: `SELECT`, `INSERT`, `UPDATE`, `DELETE`.  

3. **Data Control Language (DCL)**  
   - Manages user access and permissions.  
   - Examples: `GRANT`, `REVOKE`.  

---

## Difference Between a Primary Key and a Foreign Key
| **Aspect**         | **Primary Key**                                     | **Foreign Key**                                |
|---------------------|----------------------------------------------------|-----------------------------------------------|
| **Definition**      | Uniquely identifies a record in a table.           | Links a record in one table to another table. |
| **Uniqueness**      | Must be unique in the table.                       | Can have duplicate values.                    |
| **Nullability**     | Cannot contain `NULL` values.                     | Can contain `NULL` values.                    |
| **Purpose**         | Ensures record uniqueness within a table.          | Maintains referential integrity.              |

---

## What is an Entity-Relationship Diagram?
An **Entity-Relationship Diagram (ERD)** visually represents the entities (objects) in a database, their attributes, and the relationships between them. It is used in database design to model logical data structure.

---

## Advantages of Relational Databases
1. **Data Integrity**  
   - Ensures accuracy and consistency of data through constraints.  

2. **Flexibility**  
   - Supports dynamic queries and schema modifications.  

3. **Data Relationships**  
   - Uses keys to define and enforce relationships.  

4. **Scalability**  
   - Can handle large amounts of data efficiently.  

5. **Security**  
   - Provides robust mechanisms for access control and data encryption.  

---

## Four Types of Data Types in Tables
1. **Integer**: Stores whole numbers (e.g., `INT`, `BIGINT`).  
2. **String**: Stores text (e.g., `VARCHAR`, `CHAR`).  
3. **Date/Time**: Stores date and time values (e.g., `DATE`, `TIMESTAMP`).  
4. **Boolean**: Stores `TRUE` or `FALSE` values.  

---

## Purpose of a Database Management System (DBMS)
The purpose of a DBMS is to:
1. **Store and Organize Data**  
   - Provides structured storage for efficient access.  

2. **Ensure Data Security**  
   - Controls user access and protects data from unauthorized use.  

3. **Support Data Integrity**  
   - Maintains accuracy and consistency in data through validation and constraints.  

4. **Facilitate Data Sharing**  
   - Enables multiple users to access data simultaneously.  

5. **Provide Scalability**  
   - Handles increasing amounts of data effectively.  

6. **Enable Backup and Recovery**  
   - Protects data from loss and restores it after failures.  
