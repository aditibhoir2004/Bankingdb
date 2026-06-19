**--What are the datatypes used for the database?--**

Datatypes Used in MySQL Database

Numerical Datatypes
MySQL provides several numeric data types to store numerical values. These include exact numeric types such as INT, INTEGER, SMALLINT, DECIMAL, and NUMERIC, which store values with high precision. It also supports approximate numeric types such as FLOAT, REAL, and DOUBLE, which are used for decimal values where slight rounding may occur. These datatypes are commonly used for storing quantities, prices, marks, and other numerical information.

Date and Time Datatypes
MySQL offers various datatypes for storing date and time information, including DATE, TIME, DATETIME, TIMESTAMP, and YEAR. These datatypes help manage temporal data efficiently. The DATE datatype stores calendar dates, TIME stores time values, while DATETIME and TIMESTAMP store both date and time. These are useful for recording events, transactions, and system-generated timestamps.

String Datatypes
String datatypes are used to store text and character data. The most commonly used string types are CHAR and VARCHAR. CHAR stores fixed-length strings, whereas VARCHAR stores variable-length strings. These datatypes are suitable for storing names, addresses, email IDs, and other textual information.

Binary Datatypes (BINARY and VARBINARY)
The BINARY and VARBINARY datatypes are used to store binary data. BINARY stores fixed-length binary strings, while VARBINARY stores variable-length binary strings. These datatypes are useful when storing data that should not be interpreted as regular text.

BLOB and TEXT Datatypes
MySQL provides BLOB and TEXT datatypes for storing large amounts of data. The BLOB family includes TINYBLOB, BLOB, MEDIUMBLOB, and LONGBLOB, which are used to store binary objects such as images, audio, and files. Similarly, the TEXT family includes TINYTEXT, TEXT, MEDIUMTEXT, and LONGTEXT, which are used to store large textual content such as descriptions, documents, and comments. The main difference is that BLOB stores binary data, while TEXT stores character data.


**OLTP (Online Transaction Processing)**

Definition: Handles daily business transactions quickly and accurately.

Examples: Online banking, ATM transactions, online shopping.

**OLAP (Online Analytical Processing)**

Definition: Analyzes large amounts of data to support decision-making and reporting.

Examples: Sales analysis, business reports, data warehouses.
