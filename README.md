# React Chat App
This is a real-time chat application built with ReactJS, Tailwind CSS, web sockets, JWT authentication, and MongoDB. Users can sign up, sign in, and join chat rooms to communicate with other users in real-time.

# Features
   * User authentication using JWT tokens
   * Real-time chat using web sockets
   * View online users
   * Timestamps to show when messages were sent
   * Automatic scrolling to the latest messages
   * Responsive design using Tailwind CSS
# Technologies
  * ReactJS
  * Tailwind CSS
  * Web sockets
  * JWT authentication
  * MongoDB
  * Node.js
# Setup
To run this app locally, you will need to have Node.js and MongoDB installed on your system.

Clone this repository to your local machine using 
```git clone https://github.com/your-username/react-chat-app.git.```

In the project directory, run 
```npm install``` to install the required dependencies.

Create a .env file in the root of the project and set the following environment variables:

  * REACT_APP_API_URL=<the URL of the backend API>
  * REACT_APP_SOCKET_URL=<the URL of the socket server>
  * JWT_SECRET=<a secret key used to sign JWT tokens>
  * MONGODB_URI=<the URI of your MongoDB database>
   
Run ```npm start``` to start the app in development mode.

# Deployment
To deploy this app, you can use any cloud provider that supports Node.js and MongoDB. Here are some steps you could follow:

  * Create a new instance of a cloud server (e.g. AWS EC2 or DigitalOcean droplet).

  * Install Node.js and MongoDB on the server.

  * Clone the repository to the server using git clone https://github.com/your-username/react-chat-app.git.

In the project directory, run ```npm install``` to install the required dependencies.

Create a .env file in the root of the project and set the following environment variables:


REACT_APP_API_URL=<the URL of the backend API>
REACT_APP_SOCKET_URL=<the URL of the socket server>
JWT_SECRET=<a secret key used to sign JWT tokens>
MONGODB_URI=<the URI of your MongoDB database>
Run npm run build to build the app for production.

Start the app using a process manager like pm2 or systemd.

# Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.
