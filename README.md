# Db_connection_php

Here I have used php as a server side programming language and MySQL as a database.
To Send The form data to server side php file we have to specify php file name inside the form tag using action attribute so that this php file will execute when the this form is submitted.

We have two different method to send the data to sever GET or POST post method is more secure way to send data to the server side.

In php to get the data which is send from client side we have to use appropriate global variable if client send data using post method then we have to use $_POST if client has send using GET method then we have to use $_GET variable to get that data.

After getting the data at server side We have to do a Connection with the database. PHP provide the Full support and method to do MySQL database connection in php.

Prepare method save your query from sql injection.

Prepare method provide the binding mechanism to bind the data at run time not at compile time.
