
# Task Manager App (MEAN Stack)

This project is a Task Manager application built using the MEAN stack, which includes MongoDB, Express.js, Angular, and Node.js. It allows users to manage their tasks and to-do lists efficiently.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Authentication**: Users can create accounts and authenticate using a username and password.
- **Task Management**: Users can create, read, update, and delete tasks.
- **Task Categories**: Tasks can be organized into different categories for better organization.
- **Real-time Updates**: Utilizes WebSockets for real-time updates on tasks.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/task-manager-app.git
   ```

2. **Install Dependencies**

   Navigate to the project directory and install the required dependencies for both the server and client.

   ```bash
   cd task-manager-app
   npm install
   cd client
   npm install
   ```

3. **Database Setup**

   Set up a MongoDB database and configure the connection in the `server/config/config.js` file.

4. **Run the Application**

   Start the server and client.

   ```bash
   # Start the server
   npm start

   # Start the client (in a separate terminal)
   cd client
   ng serve
   ```

   Access the application at [http://localhost:4200](http://localhost:4200).

## Usage

- Register a new account or log in with an existing one.
- Create tasks and assign them to categories.
- Update tasks with new information or mark them as completed.
- Delete tasks when they are no longer needed.

## Technologies

- **MongoDB**: A NoSQL database used for storing task and user data.
- **Express.js**: A Node.js framework for building the server and handling HTTP requests.
- **Angular**: A front-end framework for building the user interface and interacting with the server.
- **Node.js**: A JavaScript runtime environment for executing server-side code.
- **Socket.io**: A library for enabling real-time communication between the server and clients.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository and create a new branch.
2. Make your changes and test them.
3. Submit a pull request detailing your changes.
