# e-commerce-api

## Description
A backend API for an e-commerce site.

## Installation

From the root directory of the application, run the command 'npm install'

Inside the root directory of the application create a file called '.env'

In the '.env' file, create your credentials as such:

DB_NAME=
DB_USER=
DB_PASSWORD=
DB_URL=

Use your own credentials for eac field. Do not change the variable names.

## Usage

Use PostgreSQL credentials to log in to postgres in the db/ directory and run '\i schema.sql'

After schema has run, use '\q' to quit out of psotgres and navigate one level up to the application's root directory.

Ensure you have entered the proper credentials into your own .env file (not provided by the repository) which you should locate in the root directory of the application.

Run 'npm run seed' from the root directory of the application

Run 'node server.js' from root directory. After you see the message 'App listening on port ####!' use the Insomnia application to make your requests to the server.

## Video Walkthrough
https://youtu.be/AQN9vr0LQXU

## Credits

Sequelize documentation was very helpful with remembering functions and syntax for using sequelize.

https://sequelize.org/docs/v6/core-concepts/model-querying-finders/
https://sequelize.org/docs/v6/core-concepts/model-querying-basics/

Xpert Learning Assistant by Bootcamp Spot was extremely helpful in finding hole/issues in my code.
