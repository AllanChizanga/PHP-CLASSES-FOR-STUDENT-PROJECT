# PHP-CLASSES-FOR-STUDENT-PROJECT
Well this is a very simple class for interacting with a mysql database using PDO
You can uses predefined fields and methods to get your task quickly done

lets say you want to select data in database first you change database name, username and password in this class
then you can include the class in your process.php or action.php
EXAMPLE
$conn = new Connection();
//your query
$conn->query = "SELECT * FROM table";
//preparing statement
$conn->prepare();
//selecting
$returnData = $conn->selectMulti();

// so an array is returned which you can loop through and display 

other methods include
send() // for inserting or updating data
select() // for retrieving one row only

THIS IS JUST FOR SCHOOL PROJECTS
