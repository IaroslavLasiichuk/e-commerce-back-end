# E-commerce Back-End

## Description
This is a back-end application for an e-commerce website built using the latest technologies, such as Express.js, MySQL2, and Sequelize, to help an internet retail company compete with other e-commerce companies. This application provides various routes for performing CRUD (Create, Read, Update, and Delete) operations on the Category, Product, and Tag models.

## Link
Link to walkthrough video that demonstrates the functionality of the README generator.
> https://d____________________

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Technologies](#technologies)
* [Mock up](#mockup)
* [Contributing](#contributing)
* [Questions](#questions)

## Installation

To install the application, you need to clone this repository to your local machine, navigate to the root directory of the application, and run the following command in the terminal to install the required dependencies:
    
     npm install

# Usage 
To use the application, you need to perform the following steps:

1. Create a .env file in the root directory of the application and add your MySQL database name, username, and password as follows: 

       DB_NAME='your_database_name'
       DB_USER='your_mysql_username'
       DB_PW='your_mysql_password'

2. Create a database using the schema provided in the db folder. You can use the following command in the terminal to create the database:

       mysql -u your_mysql_username -p < db/schema.sql

3. Seed the database with test data using the following command:

       npm run seed

4. Start the server by running the following command:

       npm start
5. Test the API routes using tools like Insomnia or Postman. 

## Technologies
1. Javascript
2. NodeJs
3. Mysql
4. Insomnia
5. Nodemon
6. Sequelize
7. Dotenv
8. Express

## Mock up
![Screenshot_1](./Assets/13-orm-homework-demo-01.gif)
![Screenshot_2](./Assets/13-orm-homework-demo-02.gif)
![Screenshot_3](./Assets/13-orm-homework-demo-03.gif)

## Contributing

Contributing
Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request.

## Questions

If you have any questions about this project, please feel free to reach out to me:

GitHub: https://github.com/iaroslavlasiichuk 
Email: lasmant@yahoo.com    