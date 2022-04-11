# Mysql-Command

## Command for using shell or command prompt

In terminal first you have to be in c:xampp/mysql/bin folder [Wherever you install your mysql]


### How to enter in mariaDB
<b>mysql -u root</b><br />

### How to show list of databases we have
<b>show databases;</b><br />

### How to create databases
<b>CREATE DATABASE `[name of your databases]`</b>

### How to use or Enter in the database
<b>USE `[name of the databases]`</b>

### How to create table
<b>CREATE TABLE user (
	name varchar(255) not null,
	age int(255) not null
);
</b>

### How to show tables
<b>show tables;</b>

### How to see the fields inside of the table
<b>desc `"`[table name]`"`</b>
