# Banking Simulator

## Overview

The Banking Simulator is a Java-based application that simulates basic banking operations. It allows users to create accounts, deposit and withdraw money, transfer funds, and manage account details. The application uses MySQL for data storage and follows a modular package structure for better maintainability.

## Features

* Create and manage bank accounts
* Deposit and withdraw money
* Transfer funds between accounts
* View account details
* Transaction logging
* Balance alert functionality
* MySQL database integration using JDBC

## Technologies Used

* Java
* Maven
* MySQL
* JDBC
* Object-Oriented Programming 

## Project Structure

```
src
├── main
│   ├── java
│   │   └── com.bank
│   │       ├── account
│   │       ├── alert
│   │       ├── db
│   │       ├── report
│   │       ├── transaction
│   │       └── Main.java
│   └── resources
└── test
```

## Prerequisites

* Java 17 or later
* Maven
* MySQL Server
* IntelliJ IDEA (or any Java IDE)

## Database Setup

1. Create a MySQL database named `bank_simulator`.
2. Update the database username and password in `DatabaseConnection.java`.
3. Run the required SQL script to create the necessary tables.

## How to Run

1. Clone the repository.
2. Open the project in IntelliJ IDEA.
3. Reload Maven dependencies.
4. Configure the MySQL database connection.
5. Run `Main.java`.

## Future Enhancements

* Java Swing graphical user interface
* User authentication
* Transaction history dashboard
* Account search and filtering
* REST API integration

## Author

**Preetha K**
