# CRUD-Application-using-Php-MySQL

Created a CRUD Application using PHP and MYSQL.

CRUD is an acronym that comes from the world of computer programming and refers to the four functions that are considered necessary to implement a 
persistent storage application:
  1.Create
  2.Read
  3.Update
  4 Delete.
## Creating a database

We can create a new database in MySQL by using the CREATE DATABASE statement with the below syntax:

 .  CREATE DATABASE [IF NOT EXISTS] database_name.
 .  [CHARACTER SET charset_name]
 .  [COLLATE collation_name];

##creating a table in mysql

.  You can create one table from another by adding a SELECT statement at the end of the CREATE TABLE statement:
.  CREATE TABLE new_tbl [AS] SELECT * FROM orig_tbl;
.  MySQL creates new columns for all elements in the SELECT .
