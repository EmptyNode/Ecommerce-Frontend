Welcome to the E-commerce Backend Project! This project is a robust and scalable backend solution for an e-commerce platform, built using Express.js, MongoDB, TypeScript, and Muttler middleware. It provides a powerful REST API to support both user and admin panels, offering comprehensive features including user authentication, product management, and detailed statistics on sales, customer growth, and more.
Table of Contents
Features

    Express.js: Utilizes the popular Node.js framework for building a robust and scalable backend.
    MongoDB: Uses a MongoDB database for storing and managing product information, user data, and statistics.
    TypeScript: Enhances code readability and maintainability by adding static typing to JavaScript.
    REST API: Provides a comprehensive set of RESTful endpoints for various functionalities.
    Muttler Middleware: Implements middleware for handling common tasks such as logging, error handling, and authentication.

Prerequisites

Ensure you have the following installed on your machine:

    Node.js
    MongoDB

Installation

    Clone the repository:

bash

git clone https://github.com/your-username/e-commerce-backend.git
cd e-commerce-backend

    Install dependencies:

bash

npm install

    Set up your environment variables by creating a .env file based on the provided .env.example.

    Start the server:

bash

npm start

Usage

The backend server will be running at http://localhost:3000 by default. You can now start making requests to the available endpoints.
Endpoints

Refer to the API documentation for detailed information on available endpoints and their functionalities.
Authentication

The project uses JSON Web Tokens (JWT) for authentication. Include the generated token in the Authorization header of your requests to access protected endpoints.
Middleware

Muttler middleware is employed for handling various aspects of the application, including logging, error handling, and authentication. Refer to the middleware documentation for more details.
