# e-commerce-backend

## Description  
Backend site, that builds models of the categories, products and tags. It establishes the routes for the different api requests.

## Walkthrough Video 
https://drive.google.com/file/d/1OOg2OFUtgw6qweVmWlSmW68VVrt8wKsI/view

## Installation 

* Clone repo 
* Run npm install 
* npm run seed 
* npm start

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

