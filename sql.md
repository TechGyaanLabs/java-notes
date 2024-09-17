
# SQL Basic Interview Questions

## 1. What is SQL?
SQL (Structured Query Language) is a standard programming language used to manage and manipulate relational databases. It is used for querying, updating, inserting, and deleting data in databases.

## 2. What are the different types of SQL statements?
SQL statements can be categorized into the following:
- **DDL (Data Definition Language)**: Examples: `CREATE`, `ALTER`, `DROP`.
- **DML (Data Manipulation Language)**: Examples: `SELECT`, `INSERT`, `UPDATE`, `DELETE`.
- **DCL (Data Control Language)**: Examples: `GRANT`, `REVOKE`.
- **TCL (Transaction Control Language)**: Examples: `COMMIT`, `ROLLBACK`, `SAVEPOINT`.

## 3. What is the difference between `DELETE` and `TRUNCATE`?
- **DELETE**: Removes specific rows from a table based on the condition in the `WHERE` clause. It can be rolled back.
- **TRUNCATE**: Removes all rows from a table without using a `WHERE` clause. It cannot be rolled back as it does not log individual row deletions.

## 4. What is a Primary Key?
A Primary Key is a unique identifier for each record in a database table. It must contain unique values and cannot contain NULL values. Each table can have only one primary key.

## 5. What is the difference between Primary Key and Unique Key?
- **Primary Key**: Enforces the uniqueness of the column. It does not allow NULLs.
- **Unique Key**: Also enforces uniqueness, but it allows a single NULL value.

## 6. What are Foreign Keys?
A Foreign Key is a field in a table that is a Primary Key in another table. It is used to establish a link between two tables.

## 7. What is a JOIN in SQL, and what are the types of JOINs?
A JOIN clause is used to combine rows from two or more tables based on a related column. Types of JOINs include:
- **INNER JOIN**: Returns rows that have matching values in both tables.
- **LEFT JOIN (LEFT OUTER JOIN)**: Returns all rows from the left table and matched rows from the right table.
- **RIGHT JOIN (RIGHT OUTER JOIN)**: Returns all rows from the right table and matched rows from the left table.
- **FULL JOIN (FULL OUTER JOIN)**: Returns rows when there is a match in either table.
- **CROSS JOIN**: Returns the Cartesian product of both tables.

## 8. What is a Self Join?
A Self Join is a regular join but the table is joined with itself.

## 9. What is the difference between `WHERE` and `HAVING` clauses?
- **WHERE**: Filters rows before grouping them with the `GROUP BY` clause.
- **HAVING**: Filters rows after the grouping has been performed.

## 10. What is normalization? What are its types?
Normalization is the process of organizing data in a database to reduce redundancy and improve data integrity. Types of normalization include:
- **1NF (First Normal Form)**
- **2NF (Second Normal Form)**
- **3NF (Third Normal Form)**
- **BCNF (Boyce-Codd Normal Form)**
- **4NF (Fourth Normal Form)**

## 11. What is a View in SQL?
A View is a virtual table that consists of a subset of data contained in a table. Views are not physically stored in the database; they are generated dynamically upon request.

## 12. What is an Index? How does it improve query performance?
An Index is a database object that speeds up the retrieval of rows by using pointers. It creates an entry for each value in the indexed columns, allowing for faster search and access.

## 13. What are the types of Indexes in SQL?
- **Unique Index**: Ensures that all values in the indexed column are unique.
- **Clustered Index**: Sorts the data rows in the table based on the index.
- **Non-Clustered Index**: Contains a pointer to the data in the table rather than sorting the data rows.

## 14. What is the difference between `UNION` and `UNION ALL`?
- **UNION**: Combines the result sets of two or more `SELECT` statements and removes duplicate records.
- **UNION ALL**: Combines the result sets of two or more `SELECT` statements, including duplicates.

## 15. What is a Subquery? What are its types?
A Subquery is a query nested inside another query. Types of subqueries include:
- **Single-row subquery**: Returns a single row.
- **Multi-row subquery**: Returns multiple rows.
- **Correlated subquery**: References columns from the outer query.

## 16. What is a Stored Procedure?
A Stored Procedure is a prepared SQL code that you can save and reuse. It is used to perform operations like data modification and complex calculations in the database.

## 17. What is the difference between a Stored Procedure and a Function?
- **Stored Procedure**: Can perform multiple operations and return multiple values. It can have input and output parameters.
- **Function**: Must return a single value. It is used mainly for computations and must have only input parameters.

## 18. What are Triggers in SQL?
A Trigger is a set of actions executed automatically in response to certain events on a particular table or view in a database, like `INSERT`, `UPDATE`, or `DELETE`.

## 19. What is the ACID property in SQL databases?
ACID stands for:
- **Atomicity**: Each transaction is treated as a single unit, which either completes entirely or does not happen at all.
- **Consistency**: Ensures data is in a consistent state before and after the transaction.
- **Isolation**: Transactions occur independently without interference.
- **Durability**: Once a transaction is committed, it remains so, even in the event of a system failure.

## 20. What is a Cursor in SQL?
A Cursor is a database object used to retrieve, modify, and navigate through a result set row by row. It is useful when you need to perform operations on each row in a result set individually.
