# CRUD API with MERN Stack

A simple CRUD (Create, Read, Update, Delete) API project built to learn backend development with the MERN stack. This project demonstrates how to build and interact with a backend API using Node.js, Express.js, and MongoDB.

## Features

- **Create**: Add new items to the database.
- **Read**: Retrieve items from the database.
- **Update**: Modify existing items in the database.
- **Delete**: Remove items from the database.

## Tech Stack

- **Database**: MongoDB
- **Backend Framework**: Express.js
- **Runtime Environment**: Node.js
- **Version Control**: Git

## Project Highlights

- **CRUD Operations**: Implemented basic CRUD operations using Express.js and MongoDB.
- **API Routing**: Set up RESTful API routes for handling HTTP requests.
- **Database Interaction**: Used Mongoose for object data modeling (ODM) to interact with MongoDB.
- **Error Handling**: Implemented error handling for various scenarios, such as invalid inputs or database connection issues.

## Setup Instructions

To run this project locally, follow these steps:

1. **Clone the Repository**

    ```sh
    git clone https://github.com/Pav125/CRUD-NODE-API.git
    cd CRUD-NODE-API
    ```

2. **Install Dependencies**

    ```sh
    npm install
    ```


3. **Start the Server**

    ```sh
    npm start
    ```

4. **Access the API**

    Use a tool like Postman or your browser to interact with the API endpoints at `http://localhost:5000/api`.

## API Endpoints

- **Create**: `POST /api/items`
- **Read All**: `GET /api/items`
- **Read One**: `GET /api/items/:id`
- **Update**: `PUT /api/items/:id`
- **Delete**: `DELETE /api/items/:id`

## Contribution Guidelines

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push to the branch.
5. Open a pull request.

For major changes, please open an issue to discuss what you would like to change.

## Contact

For feedback, questions, or collaboration opportunities, please reach out via devipavan824@gmail.com.
