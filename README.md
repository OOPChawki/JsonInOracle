JSON Oracle Database Storage Servlet
Project Description
This Java Servlet project, developed by Chawki Moulayat, allows users to store and retrieve JSON objects in an Oracle database. It's executed through the Payara Server and provides a user interface for inputting JSON format objects. Users can store these objects in the database and retrieve them as needed.

Features
Store JSON: Input and store JSON objects in an Oracle database.
Retrieve JSON: Fetch all stored JSON objects from the database.
Prerequisites
Java Development Kit (JDK)
Payara Server
Oracle Database
JDBC Driver for Oracle
Installation and Setup
Clone the Repository:

git clone https://github.com/OOPChawki/JsonInOracle
Configure Payara Server:

Update the payara-resources.xml with your Oracle database credentials.
Set up an Oracle connection pool in Payara Server.
(Note: Detailed instructions on setting up the connection pool can be found in the Payara documentation. Ensure the pool configuration matches your Oracle database settings.)

Deploy the Servlet:

Deploy the servlet to your Payara Server. This can be done through the Payara administration console or using the asadmin command-line tool.
Usage
Start Payara Server and Access the Servlet:

Ensure Payara Server is running.
Access the servlet through your preferred web browser.
Storing a JSON Object:

In the provided input field, enter a JSON formatted object.
Click on the 'Store' button to save the object to the database.
Retrieving Stored JSON Objects:

Click on the 'Retrieve' button to display all JSON objects stored in the database.
Contributing
Feel free to fork this repository and submit pull requests for any improvements or bug fixes.
