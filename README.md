# PHP Full Stack Backend development template

Steps to use: 
    - Clone the repo
    - Start your XAMPP or WAMP Web server for MYSQL database support 
    - Copy .env.example to .env file
    - Fill your own database credentials
    - run following command: php -S localhost:3000 public/index.php

Final command will run PHP Server and Application (😁 Yes, No need to deploy folder on Wamp! or Xampp! public endpoints)

Information about development: 
    - Store your all routes inside routes.php file, keep error-handling and 404 in the end. 
    - Use header('Content-Type: text/plain') for text/html or building FullStack web application and use header('Content-Type: application/json') for PHP Backend Rest API microservice. 