# Library Management System

Our team has created a project based on Java, NetBeans and MySQL, titled "__Library Management System__" , which is a computerized system that aims to automate the daily work of a library. It helps students and library managers keep a constant track of all the books available in the library, as well as maintain the details of users/students who borrow books.

## Table of Contents

* Features
* Technologies Used
* Setup Instructions
* Usage

## Features

1. An Admin account and a Librarian account. 
2. Display a list of all books available in the library.
3. Maintain the details of users/students to whom books have been issued.
4. Record the issued date and return date of the books.
5. Update the quantity of books in the library system whenever a book is issued/ returned.

## Technologies Used

1. Java
2. MySQL
3. NetBeans

## Setup Instructions

1. Clone the repository using the following command:

```git clone https://github.com/your-username/library-management-system.git```

2. Install MySQL and create a database named library_management_system.

3. mysql -u <username> -p library_management_system < library_management_system.sql

```mysql -u <username> -p library_management_system < library_management_system.sql```

4. Open the project in an IDE (such as Eclipse or NetBeans).
5. Update the src/main/resources/db.properties file with your MySQL database credentials.
6. Build the project using the following command:

``` mvn clean install```
## Usage
To run the application, execute the following command:

```java -jar target/library-management-system-1.0-SNAPSHOT.jar```






