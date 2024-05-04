# MONGODB-CRUD-APP-WITH-POSTMAN

[![Youtube][youtube-shield]][youtube-url]
[![Facebook][facebook-shield]][facebook-url]
[![Instagram][instagram-shield]][instagram-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

Thanks for visiting my GitHub account!

<img src ="https://www.svgrepo.com/show/331488/mongodb.svg" height = "200px" width = "200px"/> **MongoDB** is a document database. It stores data in a type of JSON format called BSON. Also, **MongoDB** is a source-available, cross-platform, document-oriented database program. Classified as a NoSQL database product, MongoDB utilizes JSON-like documents with optional schemas. [see-more](https://www.w3schools.com/mongodb/)

## CODE EXAMPLE

- [Code-Example1](https://github.com/learnwithfair/mern-ecommerce-with-postman)
- [Code-Example2](https://github.com/learnwithfair/node-express-documentation)

## Source Code (Download)

[Click Here]()

## Required Software (Download)

- VS Code, Download ->https://code.visualstudio.com/download
- Node, Download-> https://nodejs.org/en/download
- MongoDB Shell(msi) , Download-> https://www.mongodb.com/try/download/shell
- MongoDB Compass (msi), Download-> https://www.mongodb.com/try/download/community
- Postman, Download-> https://www.postman.com/downloads/

**Or Online Database (MongoDB Atlas)**

- Register -> https://www.mongodb.com/cloud/atlas/register

## ========== Environment Setup ==========

1. Install Node.js
2. To verify installation into command form by node -v
3. For initialization npm write the query in the command window as npm init -y
4. Setup the opening file into the package.json and change the file with main:'server.js'
5. To create a server using the express package then write a query into the command window as npm install express.
   Write code in the server file for initialization
   const express = require("express");
   const app = express();
   app.listen(3000, () => {
   console.log("Server is running at http://localhost:3000");
   });

6. Install the nodemon package for automatically running the server as- npm i --save-dev nodemon (For Developing purpose)
7. setup the package.json file in the scripts key, write
   "scripts": {
   "start": "node ./resources/backend/server.js",
   "dev": "nodemon ./resources/backend/server.js",
   "test": "echo \"Error: no test specified\" && exit 1"
   },
8. use the Morgan package for automatic restart. Hence install the morgan package as npm install --save-dev morgan (Development purpose)
   Write code in the server file for initialization
   const morgan = require("morgan");
   app.use(morgan("dev")); --> Middlewire.
9. Install Postman software for API testing by the URL endpoint.
10. Install Mongobd + MongobdCompass and Mongoshell (For Database)

## ========== Connect MongoDB Database ==========

1. Install Mondodb + Mongodb Compass and Mongodb Shell download from the google.
2. Set up Environment Variable in drive:c/program file
3. Create a directory in the base path of the c drive named data. Inside the data directory create another folder db.
4. Write the command in the CMD window as Mongod. And write the other command in the other CMD window as mongosh.
5. Then Check the version as mongod --version and mongosh --version.
6. Install mongoose package as npm i mongoose
7. Create an atlas account. In the atlas account create a cluster that have a user(as atlas admin) and network access with any access IP address.
8. Connect the database using URL from the atlas cluster or local Mongodb compass using the mongoose package as mongoose. connect('mongodb://localhost:27017/database-name);

## How to use this project

- clone to your local machine
- Run command in the Root directory

```cmd
npm install
npm start
```

- Import database and postman file (if Needed)
- run the project in the postman using path -> `http://localhost:8001`

## Project includes

- Node JS
- Express JS
- uuid

## Project Features

### CRUD

- Create -> insertOne() / insertMany()
- Read -> find() / findOne()
- Update -> update() / updateOne()
- celete -> delete() / deleteOne()

### Route List

- GET: /api/products -> return all products (`http://localhost:8001/api/products`)
- GET: /api/products/:id -> return single product(`http://localhost:8001/api/products/product-id`)
- DELETE: /api/products/:id -> delete the product(`http://localhost:8001/api/products/product-id`)
- PUT: /api/products/:id -> update the product(`http://localhost:8001/api/products/product-id`)
- POST: /api/products/ -> create the product(`http://localhost:8001/api/products/add-product`)

## Working Process

1.  Connect the databse
2.  Create a schema and model(collecttion/table)
3.  Create data in the databse
4.  Read data from the databse
5.  Update data from the databse
6.  Delete data from the databse

`Note: create the database -> crated the collection -> create many documents`

## Follow Me

[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/learnwithfair) [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/facebook.svg' alt='facebook' height='40'>](https://www.facebook.com/learnwithfair/) [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/instagram.svg' alt='instagram' height='40'>](https://www.instagram.com/learnwithfair/) [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/twitter.svg' alt='twitter' height='40'>](https://www.twiter.com/learnwithfair/) [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/youtube.svg' alt='YouTube' height='40'>](https://www.youtube.com/@learnwithfair)

<!-- MARKDOWN LINKS & IMAGES -->

[youtube-shield]: https://img.shields.io/badge/-Youtube-black.svg?style=flat-square&logo=youtube&color=555&logoColor=white
[youtube-url]: https://youtube.com/@learnwithfair
[facebook-shield]: https://img.shields.io/badge/-Facebook-black.svg?style=flat-square&logo=facebook&color=555&logoColor=white
[facebook-url]: https://facebook.com/learnwithfair
[instagram-shield]: https://img.shields.io/badge/-Instagram-black.svg?style=flat-square&logo=instagram&color=555&logoColor=white
[instagram-url]: https://instagram.com/learnwithfair
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/company/learnwithfair
