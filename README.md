# API_project
This is a PHP assignment to create a RESTful API.
# API_project
#API_project Requirements
API tester(POSTMAN), LAMP/XAMMP/WAMMP

#Installation
clone/Download the project filr to the htdocs server directory
Create a database in the localhost/phpmyadmin panel "clothing-company"
import the sql database in the config folder
make sure the database details specified in the config/database.php file matches with the apache web-server details.
On linux OS,make sure to activate the PDO

#Running  
open and create a new http request in your POSTMAN  application
#End points
http://localhost/API_Project/api/products/read_single.php?product_id=5
To read a single product from the products table in the database column by passing the product_id parameter
http://localhost/API_project/api/products/read.php
To read all the products from the database
http://localhost/API_project/api/customers/read_single.php?customer_id=3
To read a single customer from the customers table in the database  column by passing the product_id parameter
