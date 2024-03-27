# e-commerce-back-end
Configuring a working Express.js API and using Sequelize to interact with a MySQL database to build a back end for an e-commerce website.

## Description
  A back-end for an e-commerce website that uses latest technologies so that the company can compete with other e-commerce companies. It uses a functional Express.js API, MySQL, and sequelize to connect to a database.

  ## Table of Contents
  1. [Installation](#installation)
  2. [Usage](#usage)
  3. [Contribution](#contribution)
  4. [Testing](#testing)
  5. [Credits](#credits)
  6. [License](#license)
  7. [Questions](#questions)

  ## Installation
  This application is not deployed live, but has a functional back-end which can be tested using Insomnia. The user will need to install Dotenv version 8.2.0, express version 4.17.1, mysql2 version 2.1.0, and sequelize version 5.21.7 to the dependencies in the package.json

  ## Usage

  When using this application, the user is able to add a database name, MySQL username, and MySQL password to an enviorment variable. The user is then able to connect to the database using Sequelize. The user can then enter SOURCE db/schema.sql in the MySQL shell, and npm run seed in the command line. The developement database is created and seeded with the test data. The user can then invoke the application but running node server.js in the command line, and the sequelize models are synced to the MySQL database. The user can then use Insomnia Core to open API GET routes for categories, products, and/or tags. The data for each of these routes is displayed in a formatted JSON. The user can then test API POST, PUT, and DELETE routes in Insomnia Core and successfully create, update, and delete data from the database.

  Here is a link to the walkthrough demo video:

  

  ## Contribution
  N/A

  ## Testing
  N/A

  ## Credits
  Used Xpert Learning Assistant, used module 13 activities and mini project, and developer.mozilla.org (MDN) as resources to help create code. Also referred to sequelize documentation, referenced Challenge 13 instructions to set up models, and referenced these links:
    https://sequelize.org/docs/v6/core-concepts/model-basics/
    https://sequelize.org/docs/v6/core-concepts/assocs/
    https://sequelize.org/docs/v7/models/defining-models/
    https://www.bezkoder.com/node-js-express-sequelize-mysql/
  

  ## License
  MIT License
  ![License Badge](https://img.shields.io/badge/License-MIT-yellow.svg)
  

  For more information on this license, go to: https://opensource.org/licenses/MIT.


  ## Questions
  github.com/sjdavila210
  Email: sarahjdavila210@gmail.com
