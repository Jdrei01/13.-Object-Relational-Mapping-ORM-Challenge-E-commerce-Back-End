# 13.-Object-Relational-Mapping-ORM-Challenge-E-commerce-Back-End


# Purpose
This application serves as the backend of an e-commerce site, which uses a functional Express.js API and uses Sequelize to interact with a MySQL database.

When the user adds their database name, MySQL username, and MySQL password to an environmental variable file, the user is able to connect to a database using Sequelize. When entering schema and seed commands, a development database is created and is seeded with test data. When the application is invoked, the server is started and Sequelize models are synced to the MySQL database, with API GET routes for categories, products, and tags display a formatted JSON using Insomnia Core or Postman. When testing API POST, PUT, and DELETE routes in Insomnia Core, users can create, update, and delete data in the database.

# Built With

* JavaScript
* HTML
* CSS
* Express.js
* MySQL2 https://www.npmjs.com/package/mysql2
* Sequelize https://www.npmjs.com/package/sequelize
* dotenv package

# Usage
Clone the repository, navigate to the project folder in your CLI and use the ```npm run seed``` to seed data to the database and test CRUD routes.

Video Demonstration: 
https://drive.google.com/file/d/1-DzzryFpW95TRnI4wtDgL-L33ZIlzCui/view

# Credits
Created by Jandrei Timoteo with the help of Tutor Sandra Smith. Starter code retrieved from https://github.com/coding-boot-camp/fantastic-umbrella.

# Questions
For additional questions and information, please go to https://github.com/Jdrei01 or reach out via email at jandreitim@gmail.com.
