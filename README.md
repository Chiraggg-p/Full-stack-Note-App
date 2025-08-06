# Full-stack-Note-App

A comprehensive full-stack note-taking application built with the MERN stack (MongoDB, Express.js, React, Node.js). It allows users to register, log in, and manage their personal notes securely.
Features
User Authentication: Secure user registration and login system using JSON Web Tokens (JWT). Passwords are encrypted for enhanced security.
CRUD Operations: Full functionality to Create, Read, Update, and Delete notes.
Personalized Experience: Users can only view and manage the notes they have created.
Responsive Design: A clean and intuitive user interface that works seamlessly across different devices.
Tech Stack
The application is built using a modern technology stack:
Frontend:
React
React Router for client-side routing
Axios for making API requests
Backend:
Node.js
Express.js for the server framework
MongoDB with Mongoose for the database
JSON Web Tokens (JWT) for authorization
bcryptjs for password hashing
Development:
concurrently to run both the client and server simultaneously
nodemon for automatic server restarts during development
Getting Started
Follow these instructions to get a local copy of the project up and running.
Prerequisites
You need to have the following software installed on your machine:
Node.js
npm (Node Package Manager)
MongoDB (You can use a local installation or a cloud service like MongoDB Atlas)
Installation
Clone the repository:
Generated sh
git clone https://github.com/Chiraggg-p/Full-stack-Note-App.git
cd Full-stack-Note-App
Use code with caution.
Sh
Install backend dependencies:
Navigate to the server directory and install the required packages.
Generated sh
cd server
npm install
Use code with caution.
Sh
Install frontend dependencies:
Navigate to the client directory and install the required packages.
Generated sh
cd ../client
npm install
Use code with caution.
Sh
Set up environment variables:
In the server directory, create a file named .env and add the following variables. Replace the placeholder values with your actual data.
Generated code
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
Use code with caution.
Running the Application
You can run both the frontend and backend servers concurrently from the root directory of the project using the following command:
Generated sh
npm run dev
Use code with caution.
Sh
This will start the React development server on http://localhost:3000 and the Node.js backend server on http://localhost:5000.
