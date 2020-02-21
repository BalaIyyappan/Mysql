mysql -p -u root
Enter password:
Help-- help;

select now(),user(),version(); -- To display date time username and version of sql

CMDS:

1.create database [name]; -- To create any database
2.select database(); -- To display all the database
3.use [database_name]; --To use the database 
4.show databases; --To show all the databases
5.show tables; -- To show all the tables in the selected database
6.create table [name]( [Row info] ); -- To create any table with the row info like field and type *
7.describe/explain [table_name]; -- To describe the field and its type
8.describe [t_name] state; -- To show the contents in table
9.select * from [t_name]; -- To show all the contents of the table 
