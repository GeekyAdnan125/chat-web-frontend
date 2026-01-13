# 💬 Realtime Chat Application – Frontend

This repository contains the **frontend** of a realtime chat application built using **React + Vite** with modern UI and realtime communication support.

👉 The **backend is maintained in a separate repository**.

---

## 🚀 Tech Stack

- ⚛️ **React (Vite)** – Fast and modern frontend tooling
- 🎨 **Tailwind CSS** – Utility-first styling
- 🔌 **Socket.IO Client** – Realtime messaging
- 🌐 **REST API Integration** – Backend communication
- 🔥 **Vite HMR** – Instant hot module reload

---

## ✨ Features

- 🔐 User authentication (via backend)
- 💬 Realtime one-to-one / group chat
- 🟢 Online / offline user status
- 📡 Live message updates using Socket.IO
- 📱 Fully responsive UI
- ⚡ Fast performance with Vite

---client/
│── public/
│── src/
│ ├── components/
│ ├── context/
│ ├── pages/
│ ├── services/
│ ├── socket/
│ └── App.jsx
│── index.html
│── vite.config.js
│── package.json
## 🛠️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/GeekyAdnan125/chat-web-frontend.git
cd chat-web-frontend
2️⃣ Install dependencies
npm install
3️⃣ Environment variables

Create a .env file in the root directory:

VITE_BACKEND_URL=http://localhost:5000
VITE_SOCKET_URL=http://localhost:5000


⚠️ Make sure your backend server is running.
4️⃣ Run the development server
npm run dev


## 📁 Project Structure

