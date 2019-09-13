# Car-Rental-Java-DBMS-Project
This is a Car Rental App made in Netbeans using Java and Mysql

For using the project fork the project and clone it in your local repository.
Open the project in Netbeans IDE.

The name of the database is "rentcar"

The tables included in the MySQL database include:
1. carregistration.
2. customer.
3. Rental.

"carregistration" table includes :-

|-----------|--------------|------|-----|---------|----------------|
| Field     | Type         | Null | Key | Default | Extra          |
|-----------|--------------|------|-----|---------|----------------|
| id        | int(10)      | NO   | PRI | NULL    | auto_increment |
| car_no    | varchar(255) | YES  |     | NULL    |                |
| make      | varchar(255) | YES  |     | NULL    |                |
| model     | varchar(255) | YES  |     | NULL    |                |
| available | varchar(255) | YES  |     | NULL    |                |
|-----------|--------------|------|-----|---------|----------------|

"customer" table includes :-

|---------|--------------|------|-----|---------|----------------|
| Field   | Type         | Null | Key | Default | Extra          |
|---------|--------------|------|-----|---------|----------------|
| id      | int(10)      | NO   | PRI | NULL    | auto_increment |
| cust_id | varchar(255) | YES  |     | NULL    |                |
| name    | varchar(255) | YES  |     | NULL    |                |
| address | tinytext     | YES  |     | NULL    |                |
| mobile  | int(13)      | YES  |     | NULL    |                |
|---------|--------------|------|-----|---------|----------------|

"rental" table includes :-

|---------|--------------|------|-----|---------|----------------|
| Field   | Type         | Null | Key | Default | Extra          |
|---------|--------------|------|-----|---------|----------------|
| id      | int(10)      | NO   | PRI | NULL    | auto_increment |
| car_id  | varchar(255) | YES  |     | NULL    |                |
| cust_id | varchar(255) | YES  |     | NULL    |                |
| fee     | int(11)      | YES  |     | NULL    |                |
| date    | varchar(255) | YES  |     | NULL    |                |
| due     | varchar(255) | YES  |     | NULL    |                |
|---------|--------------|------|-----|---------|----------------|
