# E-Commerce Site

## Description

As a manager of an online retail company, I want to enhance the backend of our e-commerce website.

### User Story

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

### Acceptance Criteria

GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database

## Installation

Download the files from the repo and install locally. Be sure to install NPM, inquirer8.2.4, mysql, console.table. Then login to mysql using the following command: mysql -u root -p . Then source schema.sql. This will load the database. Then run server.js file in node to begin the application.

## Usage

This is an app local on your device that you may trigger within terminal and answer the questions

Link to video: [E-Commerce Site](https://drive.google.com/file/d/1k6td9spQm3I6b-swvIUIiXLssn7-XKxP/view)

Screenshot of App: 

![E-Commerce Site](/employee-cap.png "E-Commerce Site")

## Credits

* Worked with Tutor Andrew Tirpok



## License

MIT License
