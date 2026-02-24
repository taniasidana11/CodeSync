# 🚀 CodeSync AI — Real-Time Collaborative Code Editor

CodeSync AI is a modern **real-time collaborative coding platform** that enables multiple developers to write, edit, execute, and collaborate on code simultaneously in a shared workspace.

Built to simulate a cloud-based IDE experience, the platform supports live collaboration, AI-powered assistance, chat communication, and project-based file management directly from the browser.

---

## 🌟 Features

### 💻 Real-Time Collaboration

* Multi-user live code editing
* Instant synchronization using WebSockets
* Live cursor tracking & user presence
* Unique room-based collaboration

### 📁 File & Project Management

* Create, edit, rename, and delete files/folders
* Multi-file project workspace
* Download complete project as ZIP

### ⚡ Code Execution

* Run code directly inside browser
* Supports multiple programming languages
* Real-time output console

### 💬 Communication

* Real-time group chat
* User join/leave notifications
* Online/offline status indicators

### 🤖 AI Copilot

* AI-powered code generation
* Smart suggestions
* Insert or replace generated code

### 🎨 Developer Experience

* Syntax highlighting
* Auto language detection
* Multiple editor themes
* Adjustable font size & font family

---

## 🛠 Tech Stack

**Frontend**

* React
* TypeScript
* Tailwind CSS
* Monaco Editor

**Backend**

* Node.js
* Express.js
* Socket.IO

**Tools & Deployment**

* Docker
* GitHub
* Vercel
* Render
* Piston API

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/taniasidana11/CodeSync.git
```

### Install Dependencies

```bash
cd server
npm install

cd ../client
npm install
```

### Environment Variables

#### Backend (.env)

```
PORT=3000
```

#### Frontend (.env)

```
VITE_BACKEND_URL=http://localhost:3000
```

### Run Project

Backend:

```bash
cd server
npm run dev
```

Frontend:

```bash
cd client
npm run dev
```

Open:

```
http://localhost:5173
```

---

## 🚀 Future Enhancements

* Role-based access control
* Collaborative debugging
* Version history tracking
* GitHub integration
* Video collaboration

---

## 👩‍💻 Author

**Tania Sidana**
Full Stack Developer | MERN Stack Enthusiast

GitHub: https://github.com/taniasidana11

---

## 📄 License

This project is licensed under the MIT License.
