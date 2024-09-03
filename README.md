# User API

## Overview

This is a simple REST API built with Node.js and Express.js that performs CRUD (Create, Read, Update, Delete) operations on a user resource. The API stores user data in an in-memory array and provides endpoints to interact with the user data.

## Features

- **GET /users**: Retrieve a list of all users.
- **GET /users/:id**: Retrieve a single user by ID.
- **POST /users**: Create a new user.
- **PUT /users/:id**: Update an existing user by ID.
- **DELETE /users/:id**: Delete a user by ID.

## Prerequisites

Ensure you have the following installed on your local development environment:

- [Node.js](https://nodejs.org/) (v14.x or later)
- [npm](https://www.npmjs.com/) (Node Package Manager)

## Setup Instructions

Follow these steps to set up and run the project on your local machine:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/insigniadesign07/User-API.git


   ## Postman Collection

The Postman collection used for testing the API can be found in the `postman Rest API` directory.

### How to Use:

1. Download and install [Postman](https://www.postman.com/).
2. Import the collection by going to `File -> Import` in Postman.
3. Choose the `REST API basics- CRUD, test & variable.postman_collection.json` file from the `postman` directory.
4. The collection will now be available in your Postman workspace.
5. Use the requests in the collection to test the API endpoints.


