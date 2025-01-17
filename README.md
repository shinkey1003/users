# User Management Project

## Overview
This project demonstrates a full-stack application for managing user data, using React for the frontend and Node.js with MongoDB for the backend.

## Features
- Add user details (Name, Phone, Age, Address, Email).
- View the list of users saved in the MongoDB database.

## Prerequisites
- Node.js (https://nodejs.org/)
- MongoDB (https://www.mongodb.com/)

## Setup Instructions

### Backend Setup
1. Navigate to the `backend` folder:
   cd backend
   npm init -y
   npm install express mongoose cors body-parser

change the url if required in the server.js file
 mongodb://localhost:27017/userdb (Line no 14)
 Start the server:
node server.js

You can check api by using postman
end point http://localhost:5000/users (get)
          http://localhost:5000/users(post)
		 
### backend api
 {
  "name": "John Doe",
  "phone": "1234567890",
  "age": 30,
  "address": "123 Main Street, Cityville",
  "email": "johndoe@example.com"
}

		 
		  


### frontend Setup
cd frontend
npm install
npm start






