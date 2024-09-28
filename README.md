# Real-Time Chat Application

This is a **Real-Time Chat Application** built with **NodeJS**, **Express**, **Socket.IO**, and **React**. The app provides users with a seamless real-time messaging experience, allowing multiple users to join and chat in real-time.

![React](https://img.shields.io/badge/React-09D3AC?style=for-the-badge&logo=createreactapp&logoColor=white)
![Node](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white)
![Express](https://img.shields.io/badge/Expressjs-000000?style=for-the-badge&logo=Express&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Moment.js](https://img.shields.io/badge/Moment.js-000000?style=for-the-badge&logo=moment.js&logoColor=white)


## Tech Stack

- **Backend**: Node.js, Express, Socket.IO
- **Frontend**: React (Create React App), React Router 4, SASS
- **Utilities**: Moment.js (for timestamps)

## Features

- **Real-Time Messaging**: Built with Socket.IO for real-time communication.
- **Multi-Room Support**: Users can join different chat rooms.
- **User Notifications**: Users are notified when someone joins or leaves the chat.
- **Timestamped Messages**: Each message shows when it was sent using Moment.js.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Demo

Check out the live demo [here](#) 

## Installation

### Prerequisites

- Node.js (>= 14.x)
- npm or yarn

### Backend Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/YuriiLohvynenko/live-chat-app-react.git
   cd live-chat-app-react


2. **Install Backend Dependencies** Navigate to the server directory and install dependencies:
   ```bash
   cd Backend
   npm install

3. **Environment Setup** Create a .env file in the server directory with the following configuration:
   ```bash
   PORT=5000

4. **Run the Backend** Start the backend server:
   ```bash
   npm start

   The server will run on http://localhost:5000.

### Frontend Setup

1. **Navigate to the Frontend Directory**
   ```bash
   cd ../Frontend/app

2. **Install Frontend Dependencies**
   ```bash
   npm install

3. **Run the Frontend** Start the React app in development mode:
   ```bash
   npm start

The app will run on http://localhost:3000.

### Usage

- Open the app in two or more browser windows to simulate multiple users.
- Enter a chat room and start sending messages in real-time.
- The messages will appear instantly across all users in the same room.

### Contributing
Contributions are welcome! Please follow the contribution guidelines.
   1. Fork the repository.
   2. Create a new branch (git checkout -b feature/your-feature).
   3. Commit your changes (git commit -am 'Add feature').
   4. Push to the branch (git push origin feature/your-feature).
   5. Create a new pull request.

## License
This project is open-source and licensed under the MIT License.

*Thank you for checking out this Real-Time Chat Application! If you find this project useful, don’t forget to give it a ⭐ on GitHub.*

### Folder Structure
   ```bash
   ├── Frontend/app              # Frontend React code
│   ├── src
│   ├── public
│   ├── package.json
│   └── ...
├── Backend              # Backend NodeJS/Express code
│   ├── index.js        # Entry point for the server
│   ├── package.json
│   └── ...
└── .env                # Environment configuration




