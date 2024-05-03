# E-Commerce Back End

## Description

This is the back-end software for an e-commerce site.

## Table of Contents (Optional)

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

Download the repository from https://github.com/jinkc21/ecommerce-back-end.git

Install node.js from https://nodejs.org/en 

Install necessary files by typing "npm i" in the integrated terminal.

MySQL account is required. Register at https://www.mysql.com/
Make sure your credentials are added to a .env file within your repository. It should look similar to this example: 
 DB_NAME='ecommerce_db'
 DB_USER='root'
 DB_PASSWORD=''


Log into mysql and source the database by typing "source db/schema.sql" in mysql.

In the integrated termial, run the seeds by typing "npm run seed".

To start the server, type "npm start" in the integrated terminal.

To test the routes, Insomnia or Postman is required. 
https://insomnia.rest/
https://www.postman.com/

## Usage

In Insomnia, the server is accessed and the routes are tested.

The Products route was tested to see if all products could be accessed using the GET, POST, PUT, and DELETE method.

The Categories route was tested to see if all categories could be accessed using the GET, POST, PUT, and DELETE method.

The Tags route was tested to see if all tags could be accessed using the GET, POST, PUT, and DELETE method.

Additionally, each route was tested to see if individual routes were accessed with ids using the same methods.

For a demonstration of the functionality of the application, watch this video using this link:
https://drive.google.com/file/d/1goANl75R8Mtu7QBu414AyLJNGmXg9MGi/view

## Credits

Sequelize documentation help with model querying, validation and constraints, and associations.
https://sequelize.org/docs/v6/core-concepts/model-querying-basics/
https://sequelize.org/docs/v6/core-concepts/validations-and-constraints/
https://sequelize.org/docs/v6/core-concepts/assocs/
https://sequelize.org/docs/v6/core-concepts/assocs/#many-to-many-relationships

## License

MIT License

Copyright (c) 2024 jinkc21

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
.

---