# Collaborative Code Editor

A real-time collaborative code editor that allows multiple users to write and edit code together seamlessly. Built with modern web technologies, live synchronization, and a smooth developer experience.

---

## 🚀 Features

- ⚡ Real-time collaborative editing
- 👥 Multi-user live synchronization
- 📝 Syntax highlighting support
- 🔄 Instant updates using WebSockets
- 🌐 Shareable collaboration rooms
- 🎨 Modern responsive UI
- 🔒 Efficient state synchronization
- 📡 Low-latency communication

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Monaco Editor / CodeMirror
- Socket.IO Client

### Backend
- Node.js
- Express.js
- Socket.IO

### Other Tools
- Yjs (for collaboration)
- WebSockets
- MongoDB (optional)

---

## 📸 Preview

Add your project screenshots here.

```md
![Preview](./screenshots/preview.png)
```

---

## 📂 Project Structure

```bash
collaborative-code-editor/
│
├── client/             # Frontend
├── server/             # Backend
├── screenshots/
├── README.md
└── package.json
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/anirbandas-01/collaborative-code-editor.git
```

### 2️⃣ Navigate to project directory

```bash
cd collaborative-code-editor
```

### 3️⃣ Install dependencies

#### Frontend

```bash
cd client
npm install
```

#### Backend

```bash
cd server
npm install
```

---

## ▶️ Run Locally

### Start Backend

```bash
cd server
npm run dev
```

### Start Frontend

```bash
cd client
npm run dev
```

---

## 🌍 Environment Variables

Create a `.env` file inside the server directory.

```env
PORT=5000
MONGO_URI=your_mongodb_url
CLIENT_URL=http://localhost:5173
```

---

## 🔗 WebSocket Flow

- User joins a room
- Socket connection established
- Real-time changes synced instantly
- Multiple users edit simultaneously
- State updates broadcast to connected clients

---

## 📈 Future Improvements

- ✅ Video calling
- ✅ Authentication system
- ✅ File explorer
- ✅ Code execution support
- ✅ Multiple language support
- ✅ Dark/Light mode
- ✅ Deployment with Docker

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Anirban Das

- GitHub: https://github.com/anirbandas-01
