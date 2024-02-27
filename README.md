#Project Name: Olx for hostel


## Overview:
This repository contains the source code and assets for a hostel marketplace website, similar to OLX but specifically designed for hostel listings. The website facilitates the buying, selling, and renting of hostel accommodations.


## Features:
- User Authentication
- Hostel Listing
- Search and Filter
- Messaging System
- User Reviews and Ratings
- Responsive Design
- Admin Panel


## Technologies Used:

Frontend:
- HTML5
- CSS3
- JavaScript
- tailwind
- react.js

Backend:
- Node.js
- Express.js
- MongoDB (Database)

Authentication:
- Oauth2.0
- JSON Web Tokens (JWT)

Messaging System:
- Socket.io (for real-time communication)


## Getting Started:

Prerequisites:
- Node.js installed on your machine
- MongoDB installed and running locally or accessible via a MongoDB URI

Clone the Repository:
- git clone https://github.com/your/repository.git

Install Dependencies:
- cd repository-folder
- cp .env.example .env
- yarn

Set Environment Variables:
- Create a .env file in the root directory.

Define the following variables:
- PORT: Port number for the server 
- DB_URI: MongoDB URI for database connection
- JWT_SECRET: Secret key for JWT token generation

Run the Application:
- yarn dev
Build the Application:
- yarn build

Access the Website:
-Open a web browser and navigate to http://localhost:5173
