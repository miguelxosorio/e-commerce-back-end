# E-commerce Back End Starter Code

![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)

## Description

It's an e-commerce backend application useful for retail companies or business owners. It's run on node, mysql, and javascript. It has set up routes to perform CRUD operations wherein you can Read, Create, Update, or Delete data in your api endpoints. Basing on this application, you can perform CRUD operations on categories, products, and tags.

## Table of Contents

* [Framework](#framework)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Questions](#questions)
* [Resources](#resources)


## Framework

* `node.js`
* `express.js`
* `mysql`

## Installation

`git clone`the repo to your local machine, open your bash terminal on VS code, or use git Bash, navigate to the directory where server.js is located, run `npm init -y` on the bash command line to initiate your package.json, then go inside the file and add this `"seed": "node seeds/index.js"` inside the `"scripts": {}`. Run `npm i` on the bash command line to install dependencies. Create a `.env` file wherein you would store your DB_NAME='mysql database name', DB_USER='mysql username', DB_PW='mysql password'. Go to your cmd terminal and log in to your mysql, then run `source db/schema.sql` to initiate your database. Go back to your bash command line and run `npm run seed` to populate your database with sample data, then run `npm start` to initiate the application. 

## Usage

You can use `insomnia` or `postman` to test your api endpoints and CRUD methods.

here are the endpoints used in this application:

* `http://localhost:3001/api/categories/`
* `http://localhost:3001/api/products`
* `http://localhost:3001/api/tags`

* [Video Link]()
* ![Categories]()
* ![Products]()
* ![Tags]()


## License

This repository is licensed under the ISC license. 

## Contributing

Please refer to the email link below to contact me for any contributions to the project.

## Questions

Questions about this repository? Contact me at [miguel.osorio19@yahoo.com](mailto:miguel.osorio19@yahoo.com). View more of my work in GitHub at [miguelxosorio](https://github.com/miguelxosorio)

## Resources
* [mysql2](https://www.npmjs.com/package/mysql)
* [sequelize](https://www.npmjs.com/package/sequelize)
* [express](https://expressjs.com/)
* [Shields License and Badges](https://shields.io/category/license)