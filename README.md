# **Real-Time Chat Application**

A feature-packed real-time chat application built using the MERN stack, Socket.io, TailwindCSS, and Daisy UI. This app provides secure authentication and authorization with JWT, real-time messaging, online user status, global state management with Zustand, and robust error handling on both client and server sides.

---

## **Table of Contents**
1. [Features](#features)
2. [Tech Stack](#tech-stack)
3. [Installation](#installation)
4. [Environment Variables](#environment-variables)
5. [Build and Start the App](#build-and-start-the-app)
6. [Screenshots](#screenshots)
7. [Contributing](#contributing)
8. [License](#license)

---

## **Features**
- **Authentication & Authorization**: Secure login and signup using JSON Web Tokens (JWT).
- **Real-Time Messaging**: Powered by Socket.io for instant communication.
- **Online User Status**: See who is online in real-time.
- **Responsive Design**: TailwindCSS and Daisy UI provide a beautiful and responsive user interface.
- **Global State Management**: Zustand is used for handling global application state.
- **Error Handling**: Comprehensive error handling on both server and client sides for a smooth user experience.

---

## **Tech Stack**
- **Frontend**: React.js, TailwindCSS, Daisy UI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Real-Time Communication**: Socket.io
- **Authentication**: JWT
- **State Management**: Zustand

---

## **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/Soumyaatanna/RealTimeChatApp.git
# Environment Variable Setup

To configure the project, you need to create an `.env` file in the root directory of your project and add the required environment variables. Below is an example:

```plaintext
# MongoDB configuration
MONGODB_URI=your_mongodb_connection_string

# Server configuration
PORT=5001
NODE_ENV=development

# JWT (JSON Web Token) Secret
JWT_SECRET=your_jwt_secret

# Cloudinary configuration
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
