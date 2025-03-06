# Chat Application Backend

This is the backend of a real-time chat application built using **Node.js, Express, MongoDB, and Socket.io**. It provides authentication, user management, and real-time messaging features.

## Features
- User authentication (Register/Login)
- Fetch all users except the logged-in user
- Real-time messaging with **Socket.io**
- Store and retrieve messages from **MongoDB**
- RESTful API for user and message management

## Technologies Used
- **Node.js**
- **Express.js**
- **MongoDB (Mongoose)**
- **Socket.io**
- **Cors**
- **Dotenv**
- **JWT Authentication** (if implemented)

## Installation & Setup

1. **Clone the repository**
   ```sh
   git clone https://github.com/your-username/chat-app-backend.git
   cd chat-app-backend
## Real-Time Communication (Socket.io)
- connect - When a user connects, their socket ID is logged.
- send_message - Sends a message to the receiver and stores it in the database.
- receive_message - Listens for incoming messages.
- disconnect - Logs when a user disconnects.

