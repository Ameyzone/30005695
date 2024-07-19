# CaseStudy
This project is a menu-based console application for managing an inventory system for a retail store. It includes functionalities for managing products, suppliers, and orders, using Core Java, MySQL, and JDBC.


System Requirements
Java Development Kit (JDK) 8 or higher
MySQL Database Server
Eclipse IDE (or any other Java IDE)
MySQL JDBC Driver


Project Setup
1. Clone the Repository:
Clone the project repository to your local machine using Git.

2. Open Project in Eclipse:
Open Eclipse IDE.

3. Add MySQL JDBC Driver:
Download the MySQL JDBC Driver from MySQL Connector/J Download.

4.Database Setup
. Start MySQL Server
. Create Database and Tables:
  Open MySQL Workbench .

Execute the following SQL database and tables:
•	Product Table:
o	product_id (Primary Key)
o	name
o	category
o	price
o	quantity_in_stock

•	Supplier Table:
o	supplier_id (Primary Key)
o	name
o	contact_information
o	address

•	Order Table:
o	order_id (Primary Key)
o	product_id (Foreign Key references Product Table)
o	supplier_id (Foreign Key references Supplier Table)
o	order_date
o	quantity
o	status (placed/canceled)

5. Configure Database Connection:
Ensure the DatabaseUtil class in your project is correctly configured with your MySQL database credentials:

6. Running the Project
Run the Main Application:

Navigate the Menu:
The console application will display a menu with options to manage products, suppliers, and orders. Follow the prompts to interact with the system.

7. Troubleshooting
Common Issues:
Database Connection Error:
Ensure MySQL server is running and credentials are correct.

Class Not Found: Make sure the MySQL JDBC driver is added to the project classpath.


