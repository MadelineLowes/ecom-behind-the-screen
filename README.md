# Ecom Behind the Screens

[![Contributors][contributors-shield]][contributors-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![github][github-shield]][github-url]

## Description

 This application is built using Express.js the MySQL2, Sequelize, & dotenv packages, to create, read, update, and delete information in the database. The user can access the database by utilizing an application like Insomnia to execute GET, POST, PUT, and DELETE routes.

 It is intended to be used by employers/business owners of an internet retail company, who want to manage their e-commerce website using the latest backend technologies to make their company competitive.

## Table of Contents

- [Description](#description)
- [Getting Started](#getting_started)
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Questions](#questions)

## Getting Started

### Prerequisites

If the user doesn't already have the following installed, follow the documentation provided:

- [Node.js](https://nodejs.org/en/download/)
- [Express.js](https://expressjs.com/en/starter/installing.html)
- [MySQL2](https://www.npmjs.com/package/mysql2)
- [Sequelize](https://www.npmjs.com/package/sequelize)
- [dotenv](https://www.npmjs.com/package/dotenv)

## Installation

Users can follow the video walkthrough attached below or the steps listed.

- Clone the repo

  ```sh
  git clone https://github.com/MadelineLowes/organize-my-business
  ```

- Navigate into cloned repo

  ```sh
  cd ecom-behind-the-screens
  ```

- Install dependencies

  ```sh
  npm install
  ```

- Login to mysql

  ```sh
  mysql -u root -p // enter users mysql password
  ```

- Create the database

  ```sh
  SOURCE db/schema.sql
  ```

- Seed table to the database

  ```sh
  SOURCE db/seeds.sql
  ```

- Exit mysql

  ```sh
  quit
  ```

## Usage

Users can follow the video walkthrough attached below or the steps listed.

- Start/restart the app

  ```sh
  node server.js
  ```

- User will see a message in the terminal saying, "App listening on port 3001!"
- Open Insomnia, or a comparable application, to access the database.
- GET routes to view all

  ```sh
  localhost:3001/api/categories
  localhost:3001/api/products
  localhost:3001/api/tags
  ```

- GET routes to view by ID

  ```sh
  localhost:3001/api/categories/1
  localhost:3001/api/products/1
  localhost:3001/api/tags/1
  ```

- POST routes to create

  ```sh
  localhost:3001/api/categories
  localhost:3001/api/products
  localhost:3001/api/tags
  ```

- PUT routes to update by ID

  ```sh
  localhost:3001/api/categories/1
  localhost:3001/api/products/1
  localhost:3001/api/tags/1
  ```

- DELETE routes to delete by ID

  ```sh
  localhost:3001/api/categories/1
  localhost:3001/api/products/1
  localhost:3001/api/tags/1
  ```

Walk-through video:

## Credits

- https://dev.mysql.com/doc/refman/8.0/en/
- https://www.npmjs.com/package/mysql2
## License

This project is covered by MIT licensing.
https://opensource.org/licenses/MIT

## Questions

Madeline Lowes:

- email: madeline.lowes@gmail.com
- github profile: https://github.com/MadelineLowes

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/MadelineLowes/ecom-behind-the-screens.svg?style=for-the-badge
[contributors-url]: https://github.com/MadelineLowes/ecom-behind-the-screens/graphs/contributors
[issues-shield]: https://img.shields.io/github/issues/MadelineLowes/ecom-behind-the-screens.svg?style=for-the-badge
[issues-url]: https://github.com/MadelineLowes/ecom-behind-the-screens/issues
[license-shield]: https://img.shields.io/github/license/MadelineLowes/ecom-behind-the-screens.svg?style=for-the-badge
[license-url]: https://github.com/MadelineLowes/ecom-behind-the-screens/blob/main/LICENSE
[github-shield]: https://img.shields.io/badge/-github-black.svg?style=for-the-badge&logo=github&colorB=555
[github-url]: https://github.com/MadelineLowes/ecom-behind-the-screens