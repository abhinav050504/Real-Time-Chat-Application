 Real-Time Chat Application
A modern full-stack chat application built for instant messaging, real-time updates, and seamless user interaction. This project demonstrates a complete messaging experience using Socket.IO, Node.js, Express.js, and MongoDB.

🔎 Description
A real-time chat app that enables users to send and receive messages instantly, see who is online, and enjoy a responsive chat interface. It supports real-time communication, user authentication, typing indicators, and message persistence.

✨ Features
Real-time messaging with Socket.IO
User authentication and session management
Typing indicator for active conversations
Online/offline presence status
Persistent chat history stored in MongoDB
Responsive UI for desktop and mobile
🧰 Tech Stack
Frontend: HTML, CSS, JavaScript (React optional)
Backend: Node.js, Express.js
Real-time communication: Socket.IO
Database: MongoDB
Authentication: JWT / session-based auth
📁 Folder Structure
Real Time Chat Application/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── utils/
│   ├── server.js
│   └── package.json
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── styles/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
├── .env.example
├── README.md
└── .gitignore
⚙️ Installation
Clone the repository:
git clone https://github.com/abhinav050504/Real-Time-Chat-Application.git cd "Real Time Chat Application/Real Time Chat Application"

2. Install backend dependencies:
   ```bash
cd backend
npm install
Install frontend dependencies:
cd ../frontend npm install

4. Create a `.env` file in the backend folder and add environment variables:
   ```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
Start the application:
backend server
cd ../backend npm run dev

frontend app
cd ../frontend npm start


## 🚀 Usage

1. Open the frontend URL shown in your terminal (usually `http://localhost:3000`).
2. Register a new account or log in with existing credentials.
3. Start a chat, send messages, and watch updates appear instantly.
4. View typing status and online user presence in real time.

## 🖼️ Screenshots

> Screenshots coming soon. Replace these placeholders with real app screenshots.

## 🌱 Future Enhancements

- Add group chat support
- Implement message read receipts
- Add file and image sharing
- Enhance UI/UX with animation and theme mode
- Deploy backend and frontend to production platforms

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Make your changes
4. Commit: `git commit -m "Add feature description"`
5. Push: `git push origin feature/your-feature`
6. Open a pull request

## 📄 License

This project is licensed under the MIT License.

## 👤 Author

**Abhinav Singh**

---

Made with ❤️ for modern chat applications.

this is also Real Time Chat Application/README.md
