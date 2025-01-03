
# TeaTalk

![TeaTalk Logo](client/src/assets/logo.svg) <!-- Replace with your actual logo URL -->

## Description

TeaTalk is a real-time chat application that allows users to communicate seamlessly. Built with React on the front end and Node.js with Express on the back end, TeaTalk provides a user-friendly interface for messaging, user authentication, and avatar customization. Whether you're chatting with friends or meeting new people, TeaTalk makes communication easy and enjoyable.

## Features

- **User Authentication**: Secure login and registration process.
- **Real-Time Messaging**: Instant messaging capabilities using Socket.IO.
- **User Profiles**: Customize your profile with avatars.
- **Contact Management**: Easily manage and chat with your contacts.
- **Responsive Design**: Works on both desktop and mobile devices.

## Technologies Used

### Frontend:
- React
- React Router
- Tailwind CSS
- Styled Components
- Axios
- Socket.IO Client

### Backend:
- Node.js
- Express
- MongoDB (with Mongoose)
- Socket.IO
- Bcrypt (for password hashing)

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mukkss/TeaTalk.git
   ```

2. **Navigate to the client directory**:
   ```bash
   cd TeaTalk/client
   ```

3. **Install the client dependencies**:
   ```bash
   npm install
   ```
4. **Set up environment variables**:
   - Create a `.env` file in the `client` directory and add your REACT_APP_LOCALHOST_KEY :
     ```
     REACT_APP_LOCALHOST_KEY="chat-app-current-user
     ```
5. **Navigate to the server directory**:
   ```bash
   cd ../server
   ```

6. **Install the server dependencies**:
   ```bash
   npm install
   ```

7. **Set up environment variables**:
   - Create a `.env` file in the `server` directory and add your MongoDB connection string:
     ```
     MONGO_URL=your_mongodb_connection_string
     PORT=5000
     ```

8. **Start the server**:
   ```bash
   nodemon index.js
   ```

9. **Start the client**:
   - Open a new terminal, navigate to the `client` directory, and run:
     ```bash
     npm start
     ```

## Usage

1. Register a new account or log in with your existing credentials.
2. Set your profile avatar to personalize your account.
3. Start chatting with your contacts or explore new conversations.

## Contributing

Contributions are welcome! If you would like to contribute to TeaTalk, please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add some feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Acknowledgments

Special thanks to the contributors and libraries that made this project possible:
- Socket.IO for real-time communication.
- React for building the user interface.

## Contact

For any inquiries, please contact:

- **Mukesh**: [muksss1102@gmail.com]
- **GitHub**: [mukkss](https://github.com/mukkss)
