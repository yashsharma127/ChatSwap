# ChatSwap

A simple full-stack chat application built with React.js for the frontend and Node.js with Socket.IO for the backend. This application allows users to chat in real-time, leveraging MongoDB for database storage.

## User Interface
<img src="/readme-images/1.png" width="400" height="200"> <img src="/readme-images/2.png" width="400" height="200">
<img src="/readme-images/3.png" width="800" height="400">

## Features and Technologies used

- Real-time chat functionality using Socket.IO.

- User authentication.

- MongoDB for database storage.
 
## Prerequisites

Before you can use this application, ensure you have the following prerequisites:

- Node.js and npm installed
- MongoDB installed and running ( locally )
- Docker installed and running (optional)
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

3. (optional) If want to run using docker:

   (note 1: remember to change MONGO_URL="mongodb://localhost:27017/chat" to MONGO_URL="mongodb://<host_machine_ip>:27017/chat" in server .env
   )

   ```bash
    docker-compose up
   ```
   (note 2: if got bcrypt error run ``` docker exec -it <backend-container-id> npm rebuild bcrypt --build-from-source ```
   in terminal and re-run the above command)

4. If want to run locally:
   For Frontend :

   ```bash
    cd client
    npm install
    npm start
   ```
   For Backend:

      ```
      cd server
      npm install
      npm start
      ```

## Note

Make sure to configure MongoDB connection settings in server.js before running the server.

This application is a starting point and can be expanded with additional features and improvements. Happy chatting!
 
