# -ORM--e-commerce-back-end


## Description

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies.
SO THAT my company can compete with other e-commerce companies. This is a project that is a build with back end for an e-commerce site. Working with  Express.js API and configure it to use Sequelize to interact with a MySQL database.



## Table of Contents (Optional)

- [Installation](#installation)
- [Usage](#usage)
- [Contribute](#contribute)
- [License](#license)
- [Questions](#Questions)



## Installation
Start a new repo in the github and  clone it in the terminal and then open it in the vs code and add the started files in the new repo. You’ll need to use the MySQL2 and Sequelize packages to connect your Express.js API to a MySQL database and the dotenv package.
"dependencies": 
   "dotenv": "^8.2.0",
   "express": "^4.17.1",
   "mysql2": "^2.1.0",
   "sequelize": "^5.21.7"
  
You start the environment in the terminal with :
npm init -y
npm install mysql2
npm install sequelize
npm install dotenv
npm i express






## Usage

GIVEN a functional Express.js API
When I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I can connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started, and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes are displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE courses in Insomnia
THEN I can successfully create, update, and delete data in my database.
To start run the following command at the root of your project and answer the prompted questions:
MySQL -u root -p
Enter Password Word when promoted
source db/schema.sql
quit
npm run seed
npm start
If you want to see the project and how it click on the link:









## License
There is no license on this project  

## Contribute
If  you would like to contribute to this project, please go to my GitHub at : 

## Questions
If you have any questions about this project, please contact me at anabennett77@gmail.com 




