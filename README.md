# Node.js Express Backend with MongoDB

This repository contains the backend server for a project developed using Node.js, Express.js, MongoDB with Mongoose, JWT for authentication, and bcrypt for password hashing. The server includes user authentication and role-based access control.

## Features

- **User Authentication:** Secure user authentication using JSON Web Tokens (JWT) and bcrypt for password hashing.
- **User Roles:** Implementation of user roles (e.g., admin, user) for better access control.
- **MongoDB Integration:** Utilizes Mongoose as the Object-Document Mapper (ODM) for MongoDB to simplify database interactions.
- **Express.js Server:** A robust and scalable backend server built with Express.js.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB installed locally or a remote MongoDB connection.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ShauryaSwarup/JPMCServer
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure environment variables:
   Create a .env file in the root of your project and set the following variables:
   ```bash
   MONGO_URI = <your_mongo_db_connection_string>
   JWT_SECRET= <your_jwt_secret_key>
   ```
4. Run the server:
   ```bash
   npm start
   ```
The server should now be running on http://localhost:3000 or a port specified in your .env file.
All protected routes require a valid JWT token. Include the token in the Authorization header of your requests.

# Contributing
Feel free to contribute to this project by opening issues or creating pull requests.
