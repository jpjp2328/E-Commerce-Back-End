# E-Commerce Back End
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
Building back end of an e-commerce site, using a working Express.js API and using Sequelize to interact with a MySQL database. This will allow the user to view as well as successfully create, update, and delete data in the database using API GET, POST, PUT, and DELETE routes.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [Technology](#technology)
- [License](#license)
- [Contribution](#contribution)
- [Tests](#tests)
- [Questions](#questions)

## Installation
- To install necessary dependencies, run the following commands:
npm i OR npm install

## Usage
- To create the database using schema.sql, open MySQL terminal (Mysql -u root -p) in the 'db' folder. Once logged into the MySQL terminal by inputting your password. type 'SOURCE schema.sql'. Your database would then be created and you can simply exit MySQL terminal by typing 'exit'.
- Alternatively, you can open MySQL terminal anywhere, log into MySQL, and type 'SOURCE C:\\(filepath)\E-Commerce-Back-End\db\schema.sql' 

- To seed the data, type 'npm run seed' in the terminal in 'E-commerce-back-end' directory.

- To run the application, type 'npm start' in the terminal. Note that you have to be in the directories location where the dependencies had been installed (in this case the folder 'E-Commerce-Back-End') to run the application.

- The application would then be running and could be tested through Insomnia. User would be able to successfully view, create, update, and delete data (Products, Categories, Tags) in the database using API GET, POST, PUT, and DELETE routes.

## Demo
- Refer to this Demo Video below to guide you:
https://user-images.githubusercontent.com/110818668/202436652-6a9632b8-9b69-4d02-91d7-16960f3c1061.mp4

## Technology
- Javascript, MySQL, node.js
- npm packages/ dependencies include: dotenv, express, mysql2, sequelize
- testing: Insomnia

## License
- This project is licensed under MIT license.

## Contribution
- Please contact me for any contributions.

## Tests
- API routes could be tested through Insomnia 

## Questions
- If you have any questions feel free to contact me directly at jeffreyp2328@gmail.com. You can also find more of my work at my Github: [jpjp2328](https://github.com/jpjp2328/).

