![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)

# Kyle-E-commerce-Back-End
  
## Description
This application is the back end of an E-commerce site used to organize products by categories and/or product tags. This app allows the user to connect directly with the database to view, add, update, and delete new and existing products including the product name,  price, and stock.
  
## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions?](#contact-information)
  
## Installation
You’ll need to use the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect your Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) to use environment variables to store sensitive data, like your MySQL username, password, and database name.

Use the schema.sql file in the db folder to create your database using MySQL shell commands. Use environment variables to store sensitive data, like your MySQL username, password, and database name.

## Usage
1. Create the schema from MySQL shell using the following command 'mysql -u root -p'. Enter your MySQL password.

2. Source the schema page with the command 'SOURCE db/schema.sql' and exit the MySQL shell with the command 'exit'.

3. Seed the database using the command 'npm run seed'.

4. Use Insomnia or any other API development platform to test the view, add, update and delete functionality using the routes found in the Routes folder. 

Use this [walk-through video](https://watch.screencastify.com/v/NnWeypfMQylXyyvfkzE6) as a guide to using this application.

## License
MIT

https://opensource.org/licenses/MIT

## Contributing
No contributions needed at this time.

## Tests
No tests to perform at this time.

## Contact Information
GitHub username: [kduesler](github.com/kduesler)

Email: kyle.duesler.09@gmail.com

Use the email address above to reach the developer with any additional questions you have about this project.

