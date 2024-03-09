# Chatezzy

Chatezzy is a real-time chat application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to create accounts, join chat rooms, and engage in real-time conversations with other users. This repository contains all the code necessary to deploy and run the Chatezzy application.

## Features

- User authentication: Users can sign up for an account, log in, and log out securely.
- Real-time messaging: Users can join various chat rooms and engage in real-time conversations with other users.
- Responsive design: The application is designed to work seamlessly across various devices, including desktops, tablets, and smartphones.

## Technologies Used

- MongoDB: NoSQL database used to store user information, chat messages, and other application data.
- Express.js: Web application framework used for building the server-side logic and RESTful APIs.
- React.js: JavaScript library used for building the user interface and front-end components.
- Node.js: JavaScript runtime environment used for running the server-side code.
- Socket.io: Library for real-time, bidirectional communication between web clients and servers.

## Installation

1. Clone the repository:


2. Install dependencies for both the frontend and backend:
   -cd frontend
   -npm install
   -cd ../backend
   -npm install
3. 
4. Set up environment variables:

   - Create a `.env` file in the `backend` directory.
   - Add the following variables:
     
Replace `MONGO_DB_URI` with the MongoDB connection string and `PORT` with your port address

5. Start the frontend and backend:
   -cd frontend
   -npm start
   -cd ../backend
   -npm start
6. Access the application at `http://localhost:5000` (or the port address you have given) in your web browser.





