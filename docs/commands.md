# MySQL Commands

- best to perform these in the MySQL Workbench, but can be done in the command line, or via connection to the server
- types in all caps
- ended with semi-colons

| Command | Output |
| :-- | :-: |
| `mysql> SHOW DATABASES;` | ![showDBs](../imgs/cmd-show_databases.png) |
| `mysql> CREATE DATABASE <dbname>;` | ![createDB](./../imgs/cmd-create_database.png) |
| `mysql> USE <dbname>;` | ![useDB](../imgs/cmd-use_database.png) |
| `mysql> SHOW TABLES;` | ![showTables](../imgs/cmd-show_tables.png) |
| `mysql> DESCRIBE <tableName>;` | ![describeTable](../imgs/cmd-describe_table.png) |
| `mysql> SELECT * FROM <tableName>;` | ![selectFrom](../imgs/cmd-select_from.png) |
| `mysql> DELETE FROM <tableName> WHERE <columnName> = '<value>';` | ![deleteWhere](../imgs/cmd-delete_where.png) |

see the manual [here](./MySQL-Getting%20Started%20with%20MySQL%20manual.pdf) in this repo under *docs/*
