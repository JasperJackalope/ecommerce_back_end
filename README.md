# Homework 13 - E-Commerce Database

## Description

This project is a database schema for an e-commerce platform, which includes tables for products, categories, tags, and product tags. It also includes API routes to perform CRUD operations on the data.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## License

    This project has no license.

## Installation

Before you begin, ensure that you have the following:

- Node.js installed on your machine
- MySQL database instance
- An environment variable file (e.g. .env) that includes the following variables:
    - DB_NAME=your_database_name
    - DB_USER=your_mysql_username
    - DB_PASSWORD=your_mysql_password

## Usage

Installation:
1. Clone the repository or download the code.
2. Open a terminal window and navigate to the project directory.
3. Run "npm install" to install all the required dependencies.

Setting up the database:
1. Ensure that your MySQL database instance is up and running.
2. Create a new database in your MySQL instance with the same name specified in your .env file.
3. Open a terminal window and navigate to the project directory.
4. Run the following command to create the tables in your database: node seeds/index.js

Starting the server:
1. Open a terminal window and navigate to the project directory.
2. Run the following command to start the server: node server.js

Using the API:
1. Open Insomnia Core or any other API client.
2. Use the following endpoints to access the data:
- GET /api/categories - Returns a list of all categories in the database.
- GET /api/products - Returns a list of all products in the database.
- GET /api/tags - Returns a list of all tags in the database.
- POST /api/categories - Creates a new category in the database.
- POST /api/products - Creates a new product in the database.
- POST /api/tags - Creates a new tag in the database.
- PUT /api/categories/:id - Updates an existing category in the database.
- PUT /api/products/:id - Updates an existing product in the database.
- PUT /api/tags/:id - Updates an existing tag in the database.
- DELETE /api/categories/:id - Deletes an existing category from the database.
- DELETE /api/products/:id - Deletes an existing product from the database.
- DELETE /api/tags/:id - Deletes an existing tag from the database.
3. All data returned from the API will be in formatted JSON.

## Contributing

Starter code was provided by our instructors Bryan and Shawn. I used W3 Schools as a textbook along with previous class lessons to provide structue and code examples. Finally, I used Chat GPT to find puncutation errors. 

## Additional Information

Link to the GitHub repository: https://github.com/JasperJackalope/ecommerce_back_end

Link to the walk-through video: https://drive.google.com/file/d/1GnBkXZxLF4mGEsP-BnqUTsCODmaGvqWE/view?usp=share_link