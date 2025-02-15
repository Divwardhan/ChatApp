# MERN Stack Socket.io Chat App

## 🚀 Introduction
This is a real-time chat application built using the **MERN (MongoDB, Express, React, Node.js) stack** with **Socket.io** for WebSocket communication. The app allows users to send and receive messages in real time with a seamless user experience.

## 🔥 Features
- Real-time messaging with **Socket.io**
- User authentication with **JWT**
- Persistent chat history stored in **MongoDB**
- Typing indicators and online status tracking
- Responsive UI built with **React & Tailwind CSS**
- Private & group chat support
- Time-stamped messages
- Notifications for new messages

## 🛠️ Tech Stack
### Frontend:
- React.js (Vite)
- Tailwind CSS
- Socket.io-client
- React Router

### Backend:
- Node.js
- Express.js
- MongoDB & Mongoose
- Socket.io
- JWT Authentication
- bcrypt.js (password hashing)
- CORS & dotenv

## 🏗️ Installation & Setup

### 1️⃣ Clone the Repository:
```bash
git clone https://github.com/Divwardhan/ChatApp.git
cd mern-chat-app
npm install
```

### 2️⃣ Backend Setup:
```bash
cd backend
```
Create a `.env` file inside `server/` and add the following:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```
Start the backend server:
```bash
node server.js
```

### 3️⃣ Frontend Setup:
```bash
cd frontend
npm install
```
Create a `.env` file inside `client/` and add the following:
```env
VITE_BACKEND_URL=http://localhost:5000
```
Start the frontend development server:
```bash
npm run dev
```

## 🚀 Running the App
Once both the backend and frontend are running, open your browser and go to:
```
http://localhost:3000
```
Register an account, log in, and start chatting!

## 🔧 API Endpoints
### Authentication:
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login user & get token
- `GET /api/auth/user` - Get authenticated user details


## 📌 Future Enhancements
- ✅ Message reactions & emoji support
- ✅ File sharing (images, videos, documents)
- ✅ Read receipts & message delivery status
- ✅ Push notifications for new messages

🎉 **Happy Coding!**

