## --What is DBMS?-- 

### DBMS (Database Management System) is a software system that allows users to store, manage, update, and access data in a structured manner. It helps in organizing large amounts of information, reducing data redundancy, and ensuring easy and secure data retrieval.


## --Difference between DBMS and RDBMS?--

| No. | Feature             | DBMS                                        | RDBMS                                                    |
| --- | ------------------- | ------------------------------------------- | -------------------------------------------------------- |
| 1   | Full Form           | Database Management System                  | Relational Database Management System                    |
| 2   | Data Storage        | Stores data in files                        | Stores data in tables (rows and columns)                 |
| 3   | Relationship        | Does not support relationships between data | Supports relationships using Primary Key and Foreign Key |
| 4   | Data Redundancy     | Higher redundancy                           | Lower redundancy due to normalization                    |
| 5   | Security            | Provides basic security                     | Provides advanced security and access control            |
| 6   | Number of Users     | Supports single-user systems                | Supports multi-user systems                              |
| 7   | Normalization       | Normalization is not mandatory              | Normalization is commonly used                           |
| 8   | Transaction Support | Limited transaction support                 | Supports ACID properties for reliable transactions       |
| 9   | Scalability         | Suitable for small applications             | Suitable for large and enterprise applications           |
| 10  | Examples            | dBase, FoxPro                               | MySQL, Oracle Database, Microsoft SQL Server             |


## --Principles to Design a Database--

1) Identify the Purpose of the Database:
   Clearly define what information the database will store and manage.
2) Identify Entities:
   Determine the main objects or entities, such as Customer, Product, Employee, etc.
3) Define Attributes:
   List the properties of each entity, such as Customer Name, Address, Phone Number, etc.
4) Choose Primary Keys:
   Assign a unique identifier to each record in a table.
5) Establish Relationships:
   Define how tables are related using Primary Keys and Foreign Keys.
6) Reduce Data Redundancy:
   Avoid storing the same data multiple times.
7) Apply Normalization:
   Organize data into tables to eliminate duplication and maintain consistency.
8) Ensure Data Integrity:
   Use constraints to maintain accurate and valid data.
9) Maintain Security:
   Control access to the database and protect sensitive information.
10) Plan for Future Growth:
    Design the database so it can handle increased data and new requirements.
