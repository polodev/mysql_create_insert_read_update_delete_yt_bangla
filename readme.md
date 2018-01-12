# mysql 101 tutorial     
Here anything i put inside `<>` will be variable value. It will be different in your case. SQL is not case sensitive so uppercase and lowercase is same thing.
### to login into mysql
~~~bash
mysql -uroot -p
~~~
### to know about all database
~~~bash
show databases;
~~~

### crate a database
~~~sql
CREATE DATABASE <dbname>;
~~~
### database use  
~~~sql
USE <dbname>
~~~

### to know about all tables
~~~bash
show tables;
~~~


### Table create
~~~sql
CREATE TABLE <tableName>(
  id INT(11) AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(30) NOT NULL,
  email VARCHAR(30)
);
~~~

### to know table structures
~~~bash
describe <tableName>
~~~


### to insert a row in a table (C)
~~~sql
INSERT INTO <TABLENAME> (column1, column2) VALUES('column1value', 'column2value');
~~~

### to retrieve data from table (R)

~~~sql
SELECT <columnName>, <columnName> FROM <tableName>
SELECT * FROM <tableName>
~~~

### to update row from table (U)
~~~sql
UPDATE <tableName> SET <column>="value" WHERE <columnName>='value'
~~~
### to delete row from table (D)
~~~sql
DELETE FROM <tableName> where <columnName>='value'
~~~
