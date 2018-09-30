SQL: Structured Query Language

结构化查询语言

> SQL is a standard language for storing, manipulating and retrieving data in database.

CRUD => create, read, update, delete.

我们知道数据库是用来保存数据以供使用的，那么数据是如何保存的？

The data in RDBMS is stored in database objects called as tables.

Table is basically a collection

A database most often contains one or more tables.

数据库中的数据是保存在表中，一个数据库包含若干张表。

Each table is identified by a name (e.g. "Customers" or "Orders").

The following program is an example of a Customers table:

    +----+----------+-----+-----------+----------+
    | ID | NAME     | AGE | ADDRESS   | SALARY   |
    +----+----------+-----+-----------+----------+
    |  1 | Ramesh   |  32 | Ahmedabad |  2000.00 |
    |  2 | Khilan   |  25 | Delhi     |  1500.00 |
    |  3 | kaushik  |  23 | Kota      |  2000.00 |
    |  4 | Chaitali |  25 | Mumbai    |  6500.00 |
    |  5 | Hardik   |  27 | Bhopal    |  8500.00 |
    |  6 | Komal    |  22 | MP        |  4500.00 |
    |  7 | Muffy    |  24 | Indore    | 10000.00 |
    +----+----------+-----+-----------+----------+

其他基本概念

What is a field?

域

The fields in the CUSTOMERS table consist of ID, NAME, AGE, ADDRESS and SALARY.
  
What is a Record or Row?

What is a column?

You can check the list of databases as follow:

    SHOW DATABASES;
    
通过以下代码可以切换目前所使用的数据库：

    use testDB;
    
How do I list the tables in a MySQL database?
    
通过以下代码可以显示当前数据库中的所有表：

    show tables;

The SELECT statement is used to select data from a database.

The data returned is stored in a result table, called the result-set.

        SELECT column1, column2, ...
        FROM table_name;
        
The WHERE clause is used to filter records.

