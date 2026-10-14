E-Commerce Backend

About the Project

This backend provides RESTful APIs for an e-commerce web application. It manages user authentication, product information, shopping orders, addresses, and other application data.

Features

User registration and authentication

Product creation, retrieval, updating, and deletion

Product search and filtering

Shopping order creation and management

User address management

Order status updates

Admin order management

MongoDB database integration

Technologies Used

Node.js

Express.js

MongoDB

Mongoose

JSON Web Tokens (JWT)

REST API

Installation

Clone the repository:

git clone YOUR_GITHUB_REPOSITORY_URL

Navigate to the backend folder:

cd backend

Install dependencies:

npm install

Create a .env file in the backend folder and configure the environment variables required by your application.

Example:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

Use the actual variable names required by your code. Never commit your real credentials.

Start the server using the script configured in package.json. For example:

npm run dev

Or, if your project uses a start script:

npm start

API Overview

The backend provides API endpoints for:

Authentication and user management

Product management

Shopping cart and wishlist integration

Address management

Order creation and order history

Order status updates and administration

Refer to the application routes for the exact endpoint paths and HTTP methods.

Environment Variables

Variable

Description

PORT

Backend server port

MONGO_URI

MongoDB connection string

JWT_SECRET

Secret used for JWT authentication

Security

Keep credentials and secrets in environment variables.

Do not commit .env files.

Validate incoming request data.

Protect private routes with authentication and authorization middleware.

Author

Developed as part of a MERN stack e-commerce project.
