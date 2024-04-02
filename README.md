# Real-Time Chat App using Socket.io with Node.js/Express.js

This is a simple real-time chat application built using Socket.io with Node.js and Express.js. Socket.io enables real-time bidirectional event-based communication. With this application, users can join chat rooms, send messages, and receive messages instantly without needing to refresh the page.

## Features

- **Real-Time Communication**: Messages are sent and received instantly, providing a seamless chatting experience.
- **Multiple Rooms**: Users can create or join different chat rooms, allowing for separate discussions on various topics.
- **User Authentication**: Optionally, you can integrate user authentication to ensure that only authorized users can access the chat rooms.
- **Responsive Design**: The chat application is designed to work across various devices and screen sizes.

## Technologies Used

- **Node.js**: A JavaScript runtime built on Chrome's V8 JavaScript engine.
- **Express.js**: A web application framework for Node.js used for building APIs and web applications.
- **Socket.io**: A JavaScript library for real-time web applications that enables bidirectional communication between web clients and servers.

## Setup Instructions

1. **Clone the Repository**: Clone this repository to your local machine.

   ```bash
   git clone https://github.com/mahmudhmh/socket-chat-app.git
   ```

2. **Install Dependencies**: Navigate into the project directory and install the necessary dependencies using npm or yarn.

   ```bash
   cd socket-chat-app
   npm install
   ```

3. **Run the Server**: Start the Node.js server.

   ```bash
   node server.js
   ```

   OR

   Use `nodemon`

   ```bash
   nodemon server.js
   ```

4. **Access the Application**: Open your web browser and navigate to `http://localhost:1312` to access the chat application.

## Usage

- **Joining a Room**: Enter a username and choose a room to join. If the room doesn't exist, it will be created automatically.
- **Sending Messages**: Type your message in the input field at the bottom and press Enter to send.
- **Receiving Messages**: Messages from other users in the same room will appear instantly in the chat window.

## Contributing

Contributions are welcome! If you have any ideas, enhancements, or bug fixes, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this readme file further based on your specific project details and requirements.
