# E-Commerce Back End

## Description

This application is to be able to manipulate data for an e-commerce company. It uses mysql, express and sequalize. Also uses insomnia to get/put/delete requests.

## Table of Contents

- README file
- server.js: the base file to run the server
- package/packagelock.json: the npm packages used for this project
- seeds folder: holds all the base data to be put into the database, with an index.js file used to run the seeding of the other files
- routes folder: contains the api folder, which holds all the routing data to use the get/put/post/delete requests for each section (tags/products/categories). proper routing is included on the index.js file for each folder.
- models folder: contains the table formatting for each table as well as setting relationships between the tables in the index file
- db folder: schema to create our database, or delete if it exists and then recreate
- config folder: contains the file used to connect to the database using sequelize