# E-commerce Back End

# Built With
- Node.js
- Express
- JavaScript
- MySQL
- Sequelize

# Description
This application is the backend for an e-commerce application. It allows you to interact with a MySQL database and perform CRUD methods through Insomnia.

# Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Video](#video)

# Installation
- Create a `.env` file in the root of the application with the following format

DB_NAME=ecommerce_db
DB_USER=root
DB_PW=password

While changing the word "password" to your own password

- Clone the repository to your computer.
- Install dependencies `npm install`
- Connect to MySQL database by running `mysql -u root -p`, enter your password if prompted. From there you want to `SOURCE db/schema.sql`, then `USE ecommerce_db`, you can now quit out of MySQL.

# Usage
Once the installation for the application is completed, it is ready to be used. Run `npm run seed` to seed the data, then `npm run start`.

# Video
https://www.youtube.com/watch?v=HPqWXjj7Nog

# Made By
Tyler Sundquist
