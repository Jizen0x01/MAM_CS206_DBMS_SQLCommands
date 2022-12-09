## Creating a Database
```sql
create database database_name;
```
## Using a Database In SSMS (SQL Server Management Studio)
```sql
use DatabaseName;
```

## Creating a Schema
```sql
create schema schema_name;
```
## Creating a Table
```sql
create table table_name(
"column_name datatype constraint"
"you can insert columns without constraints too ¯\_(ツ)_/¯"

first_name varchar(10) not null,
mobile_Number varchar(10) unique,
id int primary key,
text varchar(max) not null 

);
```
## Creating a Table into a Schema
```sql
create schemaName.tableName(

first_name varchar(10) not null,

);
```
## Deleting/Dropping a Database/Table/Schema
```sql
drop table tableName;
drop database databaseName;
drop schema schemaName;
```

## Inserting Data into a table
```sql
insert into tableName values (values);
insert into tableName (columnList) values (values);
```
