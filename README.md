# SQL-joins-
SQL joins are used to retrieve data from multiple tables. A SQL JOIN is performed whenever two or more tables are listed in a SQL statement.

SIX different types SQL joins :
* SQL INNER JOIN : It returns only Matching rows from Both Tables
  * SYNTAX :
          SELECT columns
          FROM table1
          INNER JOIN table2
          ON table1.column = table2.column;

* SQL OUTER JOIN : Returns all rows from the left table and matching rows from the right table.
  * SYNTAX :
          SELECT columns
          FROM table1
          LEFT JOIN table2
          ON table1.column = table2.column;

* SQL RIGHT OUTER JOIN : Returns all rows from the Right Table and matching rows from the left table.
    * SYNTAX :
          SELECT columns
          FROM table1
          RIGHT JOIN table2
          ON table1.column = table2.column;


* SQL FULL OUTER JOIN: Returns all rows from the both tables, with NULL values in columns where there is no match.
    * SYNTAX :
          SELECT columns
          FROM table1
          FULL OUTER JOIN table2
          ON table1.column = table2.column;

* SQL SELF JOIN :  A self join is a regular join, but the table is joined with itself.It is also                       called Cartesian join.
    * SYNTAX :
          SELECT column_name(s)
          FROM table1 T1, table1 T2
          WHERE condition;

* SQL CROSS JOIN : The CROSS JOIN  returns all records from both tables  where it perform M x N 
                     action. Also called MxN join.
    * SYNTAX :
          SELECT column_name(s)
          FROM table1
          CROSS JOIN table2;
  
