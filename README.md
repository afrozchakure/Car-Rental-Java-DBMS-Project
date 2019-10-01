# Car-Rental-Java-DBMS-Project
This is a Car Rental App made in Netbeans using Java and Mysql

For using the project fork the project and clone it in your local repository.
Open the project in Netbeans IDE.

The name of the database is "rentcar"

The tables included in the MySQL database include:
1. carregistration.
2. customer.
3. rental.
4. login.
5. returncar.

1. "carregistration" table includes :-

| Field     | Type         | Null | Key | Default | Extra          |
|-----------|--------------|------|-----|---------|----------------|
| id        | int(10)      | NO   | PRI | NULL    | auto_increment |
| car_no    | varchar(255) | YES  |     | NULL    |                |
| make      | varchar(255) | YES  |     | NULL    |                |
| model     | varchar(255) | YES  |     | NULL    |                |
| available | varchar(255) | YES  |     | NULL    |                |


2. "customer" table includes :-

| Field   | Type         | Null | Key | Default | Extra          |
|---------|--------------|------|-----|---------|----------------|
| id      | int(10)      | NO   | PRI | NULL    | auto_increment |
| cust_id | varchar(255) | YES  |     | NULL    |                |
| name    | varchar(255) | YES  |     | NULL    |                |
| address | tinytext     | YES  |     | NULL    |                |
| mobile  | int(13)      | YES  |     | NULL    |                |


3. "rental" table includes :-

| Field   | Type         | Null | Key | Default | Extra          |
|---------|--------------|------|-----|---------|----------------|
| id      | int(10)      | NO   | PRI | NULL    | auto_increment |
| car_id  | varchar(255) | YES  |     | NULL    |                |
| cust_id | varchar(255) | YES  |     | NULL    |                |
| fee     | int(11)      | YES  |     | NULL    |                |
| date    | varchar(255) | YES  |     | NULL    |                |
| due     | varchar(255) | YES  |     | NULL    |                |

4. "login" table includes :-

| Field    | Type         | Null | Key | Default | Extra          |
|----------|--------------|------|-----|---------|----------------|
| login_id | int(11)      | NO   | PRI | NULL    | auto_increment |
| username | varchar(255) | YES  |     | NULL    |                |
| password | varchar(255) | YES  |     | NULL    |                |

5. "returncar" table includes :-

| Field       | Type         | Null | Key | Default | Extra          |
|-------------|--------------|------|-----|---------|----------------|
| id          | int(10)      | NO   | PRI | NULL    | auto_increment |
| carid       | varchar(255) | YES  |     | NULL    |                |
| custid      | varchar(255) | YES  |     | NULL    |                |
| return_date | varchar(255) | YES  |     | NULL    |                |
| elap        | int(11)      | YES  |     | NULL    |                |
| fine        | int(11)      | YES  |     | NULL    |                |

