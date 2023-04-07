# Code-Titans
Code Titans is a blogging platform for computer science students to share their knowledge, insights, ideas and experiences about software development.

# Table of Contents
- [Features](#Features)
- [Technologies Used](#Technologies-Used)
- [Installation](#Installation)
- [Usage](#Usage)
- [License](#License)

## Features
- User authentication and authorization for creating and managing posts
- CRUD functionality for posts and comments
- Markdown support for writing posts
- Search functionality for finding posts by title, author, or keyword
- Pagination for organizing posts into pages

## Technologies Used
- Vue.js for the frontend
- Tailwind CSS for styling
- Express.js for the backend
- MongoDB for the database

## Installation
To install and run this project on your local machine, follow these steps:
- Clone the repository to your local machine 'git clone https://github.com/aine-dickson/Code-Titans.git'
- Install the dependencies for the frontend and backend:
cd code-titans
npm install
cd server
npm install
- Create a .env file in the root directory of the project and set the following environment variables:
DB_URI=<your-mongodb-uri>
JWT_SECRET=<your-jwt-secret>

## Usage
To start the development server, run the following command in the root directory of the project:
npm run dev
This will start both the frontend and backend servers concurrently. You can access the frontend at http://localhost:8080 and the backend at http://localhost:5000.

To build the frontend for production, run the 'npm run build command in the code-titans directory
This will generate a production-ready build of the frontend in the dist directory.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
