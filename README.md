# ChatSwap

A simple full-stack chat application built with React.js for the frontend and Node.js with Socket.IO for the backend. This application allows users to chat in real-time, leveraging MongoDB for database storage.

## User Interface
<img src="/readme-images/1.png" width="400" height="200"> <img src="/readme-images/2.png" width="400" height="200">
<img src="/readme-images/3.png" width="400" height="400">

## Features and Technologies used

- Real-time chat functionality using Socket.IO.

- User authentication.

- MongoDB for database storage.
 
## Prerequisites

Before you can use this application, ensure you have the following prerequisites:

- Node.js and npm installed
- MongoDB installed and running ( locally )
- Git and GitHub account (for hosting)

## Setup

1. Clone this repository (if you haven't already):

   ```bash
   git clone https://github.com/yashsharma127/ChatSwap.git
   cd ChatSwap
   ```

2. Now rename env files from .env.example to .env

   ```bash
    cd client
    mv .env.example .env
    cd ..
    cd server
    mv .env.example .env
    cd ..
   ```

3. For Frontend :

   ```bash
    cd client
    npm install
    npm start
   ```

4. For Backend:

   ```
    cd server
    npm install
    npm start
   ```

## Note

Make sure to configure MongoDB connection settings in server.js before running the server.

This application is a starting point and can be expanded with additional features and improvements. Happy chatting!
 
