
# Small scale Relational database management System

## About

   A database is a collection of data. A DBMS is a database management system, a software system that assists in the creation, retrieval, and placement of data in a database.

In this Project , I have  implemented the database management system with the help of the file Handling in C++  to clearly understand the working of actual database management systems.
## Objectives 


1) To Learn about a relational database Management System
2) To Learn about a relational databases
3) To know about the creation, Maintenance of Relational Database Management System (RDBMS) 
## Development
The primary languages - C++. 
 The flow of the system is :

* It can be run in Windows/DOS since it is  EXE file.
* Database Schema and database table   files are created automatically in the environment after commands are executed successfully .
## commands  of Small scale Relational database management System
    
    1) CREATE 

         Info: Creates a new table
         Format:
         CREATE TABLE table_name (
            attribute_1 attribute1_type CHECK (constraint1),
            attribute_2 attribute2_type,
            ... ,
            PRIMARY KEY ( attribute_1, attribute_2 ),
            FOREIGN KEY ( attribute_y ) REFERENCES table_x ( attribute_t ),
            FOREIGN KEY ( attribute_w ) REFERENCES table_y ( attribute_z )...
            );

    2) INSERT

        Info : INSERT INTO statement is used to insert new records in a table.
         Format: 
         INSERT INTO table_name values ( val1 , val2 , val3 
         
    3)SELECT
      Info : To select data from a database.
      Format : 
      SELECT * FROM table_name WHERE condition

    4) DROP 

       Info: To delete a whole table
       Format : 
       DROP table_name

    5) DELETE

        Info: Deletes data from a database
        Format:
        DELETE FROM table_name WHERE condition_list;

    6) UPDATE
       Info: Updates data in a database
       Format:
       UPDATE table_name
       SET column1 = value1, column2 = value2, ...
       WHERE condition;

    7) HELP

        Info: To get help regarding Syntax of commands

    8) DESCRIBE

         Info : To describe Schema of Database

    9) QUIT
       Info : To exit from System 
        

        
## Run Locally


#### Prerequisites
```
C++ IDE (C++11 or higher)
```

#### Clone the project

```bash
  git clone https://github.com/Siddhantshelake/Small-scale-Relational-database-management-System.git
```

```

 1) Open the file using C++ Compiler such as Dev C++ etc.
 2) Paste the source code and save the file in any of the computer locations.
 3) Compile the project using compile option.
 4) There is no error in the source code, Now run the project.
 5) The executable .exe file will be generated in the location you choose.
```


## Screenshots

#### CREATE
![App Screenshot](https://github.com/Siddhantshelake/Small-scale-Relational-database-management-System/blob/master/public/create.PNG)


#### DROP
![App Screenshot](https://github.com/Siddhantshelake/Small-scale-Relational-database-management-System/blob/master/public/drop.PNG)


#### INSERT INTO
![App Screenshot](https://github.com/Siddhantshelake/Small-scale-Relational-database-management-System/blob/master/public/insert.PNG)

#### DESCRIBE & HELP
![App Screenshot](https://github.com/Siddhantshelake/Small-scale-Relational-database-management-System/blob/master/public/des%20and%20help.PNG)

#### SELECT
![App Screenshot](https://github.com/Siddhantshelake/Small-scale-Relational-database-management-System/blob/master/public/select.PNG)
