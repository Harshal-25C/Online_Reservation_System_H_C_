# Online Reservation System

> This is a simple Java application for an Online Reservation System, developed by [Harshal-25c](https://github.com/Harshal-25c).

## Introduction

This project provides a basic implementation of an online reservation system that allows users to perform various operations such as adding, deleting, and viewing reservations. It uses MySQL database for data storage and JDBC for database connectivity.

## Features

- User authentication: Users can log in using their username and password.
- CRUD operations: Users can perform CRUD operations (Create, Read, Update, Delete) on reservations.
- Randomly generated PNR numbers for each reservation.
- Easy-to-use command-line interface.

## Requirements :
Ensure you have installed These on your system

> - Java Development Kit (JDK) : [Install JDK](https://www.oracle.com/in/java/technologies/downloads/).
  - MySQL Database : [Download MySQL on your system](https://www.mysql.com/downloads/).
  - JDBC Driver : [Setup JDBC Connecter](https://dev.mysql.com/downloads/connector/j/).

## Installation

(1). **Clone the repository :**

   ```bash
   git clone https://github.com/Harshal-25c/Online-Reservation-System.git
   ```


(2). **Set up the MySQL database :**

- Create a database named 'harshal' (you can change this in the code).
- Import the SQL script provided in the repository to create the necessary table (reservations).


(3). **Configure the database connection :**

- Open the `Task_1.java` file.
- Modify the url , username , and password variables in the main method according to your `MySQL database` configuration.
   
