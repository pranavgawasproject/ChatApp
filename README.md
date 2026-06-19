# 💬 ChatApp

> A real-time full-stack chat application with JWT auth, Socket.io messaging, and a clean React UI — built as a learning-friendly MERN reference project.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248)](https://mongodb.com)
[![Express](https://img.shields.io/badge/Express-Backend-000)](https://expressjs.com)
[![React](https://img.shields.io/badge/React-Frontend-61DAFB)](https://react.dev)
[![Socket.io](https://img.shields.io/badge/Socket.io-Realtime-010101)](https://socket.io)

## ✨ Features

- ⚡ **Real-time Messaging** — Socket.io powered instant delivery
- 🔐 **JWT Authentication** — secure signup / login with HTTP-only cookies
- 💬 **Conversations** — thread-based message history
- 👥 **User Sidebar** — search & start new conversations
- 🟢 **Online Status** — live presence indicators
- 🛡️ **Route Protection** — middleware-guarded APIs
- 🐳 **Devcontainer** — one-click setup with Docker

## 🛠️ Tech Stack

**Frontend:** React, Vite, Tailwind, React Router, React Hot Toast, React Icons
**Backend:** Node.js, Express, MongoDB, Mongoose, Socket.io, JWT, bcryptjs
**Dev:** Docker devcontainer, GitHub Dependabot

## 📁 Project Structure

```
.
├── backend/
│   ├── controllers/   # auth, user, message
│   ├── db/            # MongoDB connection
│   ├── middleware/    # protectRoute
│   ├── models/        # user, conversation, message
│   ├── routes/        # auth, user, message
│   ├── socket/        # socket.io server
│   ├── utils/         # generateToken
│   └── server.js
└── frontend/          # React app
    └── src/
        └── components/messages/...
```

## 🚀 Getting Started

```bash
# Backend
cd backend
npm install
echo "MONGO_URI=...
PORT=5000
JWT_SECRET=..." > .env
npm run dev

# Frontend
cd frontend
npm install
npm run dev
```

Open `http://localhost:5173`, sign up, and start chatting.

## 🐳 Devcontainer (optional)

Open in VS Code → "Reopen in Container" → backend on `:5000`, MongoDB included via docker-compose.

## 📜 License

[MIT](LICENSE) © 2026 Pranav Gawas
