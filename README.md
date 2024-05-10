# MOD13-E-commerce-Back-End 
# E-Commerce Back End
Module 13 Object-Relational Mapping (ORM): E-Commerce Back End

---

## Web Links

Repository: 

Video Walkthrough: 


---

## Description 
```
This task requires building the back end for an e-commerce site. Starter code has been given. 
The goal is to configure a working Express.js API to use Sequelize to interact with a SQL database.
```

### User Story
```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

### Acceptance Criteria 
```md
GIVEN a functional Express.js API
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

## Installation
```
npm install 
```

## Usage
```
1. Ensure all dependancies are installed: Express, Postgres, SQL, Node.
```
2. Create .env file and ensure appropriate credentials are entered. 
```
source db/schema.sql (using DBEAVER)
npm run seed
node server.js

```
Database was created using DBeaver.
Testing of the code was completed in Insomnia.

## Resources/Credit

Created by SongBirdCode with assistance from tutors as needed. 

## Features
* Express.js
* Node
* Sequelize

## Images
