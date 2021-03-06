# 13) ORM: E-Commerce-Back-End

For this project I had to build the back end for an e-commerce site by modifying starter code. Utilised Express.js to use Sequelize to interact with a MySQL database. I utilised the following technologies for this project:

- Javascript
- Node.js
- MySQL
- Sequelize
- Express.js

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
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
```

## Instructions

Ensure Mysql is installed and running on your system.

Make sure all dependencies are installed by typing ``` npm i ``` in the console.

Then enter ``` source db/schema.sql ``` into the MySQL shell.

Then return to the console and type ``` npm run seed ``` to seed the example data into the database.

Finally to start the server, type ``` npm start ``` into the console.

## Demo
* Start Server: https://drive.google.com/file/d/18HMX2w6LBDg9dsgdfZMq6Nf4rjkCNYAW/view
* Categories Routes: https://drive.google.com/file/d/1SOXLdVLslOpK-dmGodV3Cpz-q7W9mbFR/view
* Products Routes: https://drive.google.com/file/d/1zj_9BNVX2Bok9Zj8e5tsL2F--ZPLoY8E/view
* Tags Routes: https://drive.google.com/file/d/1n6xaC-m7sgQohGWjYd2flX0nYjexFltx/view
* All Routes (use case example): https://drive.google.com/file/d/1W916iMKN33wU_ckyxfX7uboluIvCVpdt/view


## Credits

University of Birmingham
