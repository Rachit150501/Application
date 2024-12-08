                                                  Database CRUD Operations Application
This Java application allows users to perform basic CRUD (Create, Read, Update, Delete) operations on a database using a graphical user interface (GUI). It connects to a MySQL database and enables inserting, updating, and deleting records for user information (Name, Email, Phone Number, Address).

Features
Insert Data: Add new user records with Name, Email, Phone, and Address.
Update Data: Update existing user records using their name.
Delete Data: Remove user records by name.
Database Connection: Uses MySQL for storing user data.
Requirements
Java (JDK 8 or higher)
MySQL Database Server
JDBC Driver for MySQL
Setup Instructions
Clone the repository:

git clone https://github.com/yourusername/database-crud-application.git
Set up the database:

Create a MySQL database named testdb (or change the database name in the code).
Create a table named users with the following columns:



CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    
    name VARCHAR(100),
    
    email VARCHAR(100),
    
    phone VARCHAR(15),
    
    address TEXT
);


Configure the database connection:

Open the code and update the connection string in the connect() method if needed.
Ensure the database username and password match your MySQL credentials.
Run the application:

Compile and run the Java application using your IDE (e.g., NetBeans, IntelliJ IDEA, or Eclipse) or command line.
Example command to run:

java NewJFrame
Perform CRUD operations:

Use the interface to insert, update, or delete user data.
Screenshots
(Provide any screenshots of the application if you want to show the GUI.)

License
This project is open-source and available under the MIT License.

Acknowledgments
MySQL for the database.
JDBC for connecting Java to MySQL.
Nimbus Look and Feel for the user interface.

PHOTO :






![image](https://github.com/user-attachments/assets/da26e46d-65d5-482a-b756-9d26c17faaf7)



