# Eat-Da-Burger! Burger
Eat-Da-Burger! - Node Express Handlebars Application


## Overview

Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat. Whenever a user submits a burger's name, your app will display the burger on the left side of the page -- waiting to be devoured. Each burger in the waiting area also has a Devour it! button. When the user clicks it, the burger will move to the right side of the page. Your app will store every burger in a database, whether devoured or not.


## Running the application
### 1. Heroku Launch

The application can be launched from the following link to Heroku:

- https://damp-sea-39391.herokuapp.com/


- OR - 

### 1. Install NPM

- NPM (Node Package Manager) (https://docs.npmjs.com/getting-started/installing-node)


### 2. Install mySQL

- mySQL (https://dev.mysql.com/downloads/installer/)


### 3. Install NPM Packages

  Install the packages from the terminal in the folder the application was cloned.

- MYSQL(https://www.npmjs.com/package/mysql)
- Body Parser (https://www.npmjs.com/package/body-parser)
- Express (https://www.npmjs.com/package/express)
- Express Handlebars (https://www.npmjs.com/package/express-handlebars)
- Method Override (https://www.npmjs.com/package/method-override)


### 4. Clone the application

  Clone the application from the following location... (https://github.com/cbessjr/CustomerView)


### 5. SQL Schema and Seed

- Run the schema (found in schema.sql) to create the database
- Run the seeds (found in seeds.sql) to populate the database
   
 
### 6. SQL Connection Update
 
  Once the application has been cloned, access the connection.js to update the user and password options in the code.     This is a neccessary step to allow the database connection.
 
 
### 7. Using the Application
 
  Once the application is loaded a list of the items (in the database). The list is a list of burgers that are retained as the application is used. Input the names of burgers you would like to eat. As the burger names are generated to the page you can click the devour button to "eat" the burger.
  
  
  
  ### Future Updates
  
  - Fix the functionality for the application which is currently receiving a /GET error generating the page. This is currently being researched.
