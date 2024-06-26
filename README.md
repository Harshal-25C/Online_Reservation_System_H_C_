# Online Reservation System

> This is a simple Java application for an Online Reservation System, developed by [Harshal-25c](https://github.com/Harshal-25c).

## Introduction :

This project provides a Basic Implementation of an Online Reservation System that allows users to perform various operations such as Adding, Deleting, and Viewing Reservations. It uses `MySQL database` for data storage and `JDBC` for database connectivity.

## Features :

- User authentication : Users can log in using their `MySQL username` and `MySQL password`.
- `CRUD` operations : Users can perform CRUD operations (Create, Read, Update, Delete) on reservations.
- Randomly generated PNR numbers for each reservation.
- Easy-to-use command-line interface.

## Requirements :
Ensure you have installed These on your system

> - Java Development Kit (JDK) : [Install JDK](https://www.oracle.com/in/java/technologies/downloads/).
> - MySQL Database : [Download MySQL on your system](https://www.mysql.com/downloads/).
> - JDBC Driver : [Setup JDBC Connecter](https://dev.mysql.com/downloads/connector/j/).

## Installation :


(1). **Set up the MySQL database :**

- Create a database named 'harshal' (you can change this in the code).
- Import the SQL script provided in the repository to create the necessary table (reservations).


(2). **Configure the database connection :**

- Open the `Task_1.java` file.
- Modify the url , username , and password variables in the main method according to your `MySQL database` configuration.

(3). **Compile and run the application :**

   ```bash
   javac Task_1.java
   java Task_1
   ```

## MySQL Database :
![Harsh1](https://github.com/Harshal-25C/Online_Reservation_System_H_C_/blob/main/images/SQL_database.png)

## Usage :

- Run the Application.
- Log in using your MySQL username and password.

Choose an option from the menu :

>  1. Insert Record
>  2. Delete Record
>  3. Show All Records
>  4. Exit

## Contributing :
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
- [ Harshal Choudhary ] - [ harshalchoudhary340@gmail.com ].

## LICENSE :
[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

MIT License

Copyright (c) 2024 Harshal Choudhary

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
   
