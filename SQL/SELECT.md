#SQL SELECT Statement
The SELECT statement is used to select data from a database.

The data returned is stored in a result table, called the result-set.
```
SELECT Syntax
SELECT column1, column2, ...
FROM table_name;
```
Here, column1, column2, ... are the field names of the table you want to select data from. If you want to select all the fields available in the table, use the following syntax:

```
SELECT * FROM table_name;
```

#SELECT Column Example
The following SQL statement selects the "CustomerName" and "City" columns from the "Customers" table:

Example
```
SELECT CustomerName, City FROM Customers;
```

SELECT * Example
The following SQL statement selects all the columns from the "Customers" table:

Example
```
SELECT * FROM Customers;
```