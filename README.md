# House Rental App

A full-stack MERN (MongoDB, Express.js, React.js, Node.js) web application that simplifies the process of renting and managing properties. The platform supports multiple user roles including renters, property owners, and administrators.

## Features

### User Authentication

* User registration and login
* Secure password encryption
* JWT-based authentication
* Forgot password functionality

### Renter Features

* Browse available properties
* View property details
* Book rental properties
* Manage bookings
* User dashboard

### Owner Features

* Add new properties
* Edit property information
* View all listed properties
* Manage booking requests
* Owner dashboard

### Admin Features

* Manage users
* Manage properties
* View all bookings
* Admin dashboard
* Monitor platform activities

## Tech Stack

### Frontend

* React.js
* Vite
* React Router
* Tailwind CSS
* Axios

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Bcrypt

## Project Structure

House-Rental-App/

├── client/

│   ├── src/

│   ├── public/

│   └── package.json

├── server/

│   ├── controllers/

│   ├── models/

│   ├── routes/

│   ├── middlewares/

│   └── package.json

└── README.md

## Installation

### Clone Repository

git clone <repository-url>

### Frontend Setup

cd client

npm install

npm run dev

### Backend Setup

cd server

npm install

npm start

## Environment Variables

Create a `.env` file in the server directory and add:

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

PORT=5000

## Future Enhancements

* Online payment integration
* Property image gallery
* Advanced search and filtering
* Property reviews and ratings
* Email notifications
* Real-time chat system

## Author

Sridevi Sarampati

## License

This project is developed for educational and learning purposes.
