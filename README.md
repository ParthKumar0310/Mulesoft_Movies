# Mulesoft_Movies
JDBC stands for Java Database Connectivity. JDBC is a Java API to connect and execute the query with the database. It is a part of JavaSE (Java Standard Edition). JDBC API uses JDBC drivers to connect with the database.

API (Application programming interface) is a document that contains a description of all the features of a product or software. It represents classes and interfaces that software programs can follow to communicate with each other. An API can be created for applications, libraries, operating systems, etc.
Before JDBC, ODBC API was the database API to connect and execute the query with the database. But, ODBC API uses ODBC driver which is written in C language (i.e. platform dependent and unsecured). That is why Java has defined its own API (JDBC API) that uses JDBC drivers (written in Java language).

We can use JDBC API to handle database using Java program and can perform the following activities:

 1.Connect to the database

 2.Execute queries and update statements to the database

 3.Retrieve the result received from the database.

In this program we have to use the Mysql database which will be connected to the Java using the concept of the JDBC. In this I have created the four files:

 1.create_table.java: In this program we have created the connection of jdbc and creted the table "movies".

 2.movies_isert.java: In this program we insert the values in the table movies using java language.

 3.retrive_movies.java: In this program we to retrive the data.

 4.query_use.java: In this program we will use the query sql to retrive the data based on the conditions.
