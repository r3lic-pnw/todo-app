# Todo App Backend

This is a simple backend for a Todo application built with Node.js, Express, and MongoDB.

## Features

-   Create, Read, Update, and Delete todos
-   RESTful API

## Prerequisites

-   [Node.js](https://nodejs.org/)
-   [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) account

## Getting Started

1.  Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```
3.  Create a `.env` file in the `config` directory and add your MongoDB connection string:
    ```
    MONGO_URI=YOUR_MONGO_URI
    ```
4.  Start the server:
    ```bash
    npm start
    ```

The server will be running on `http://localhost:5000`.

## API Endpoints

-   `GET /api/v1/todos`: Get all todos
-   `GET /api/v1/todos/:id`: Get a single todo
-   `POST /api/v1/todos`: Create a new todo
-   `PUT /api/v1/todos/:id`: Update a todo
-   `DELETE /api/v1/todos/:id`: Delete a todo