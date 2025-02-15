# CollabCode - Real-Time Collaborative Code Editor

CollabCode Live is a real-time collaborative code editor that allows multiple users to edit code in the same room. Built using **Next.js, Node.js, Express, and Socket.io**, this project provides a seamless experience for remote pair programming and coding interviews.

## Features
- ✨ **Real-time collaboration**: Multiple users can edit code simultaneously.
- 🏠 **Room-based sessions**: Create or join coding rooms with unique room IDs.
- 🎨 **Syntax highlighting**: Supports multiple programming languages.
- ⚡ **Fast and lightweight**: Uses WebSockets for instant updates.
- 🔒 **Secure rooms**: Only users with the room ID can join the session.
- 🌍 **Cross-platform support**: Works on any modern browser.
- 🚀 **Next.js-powered performance**: Optimized frontend with server-side rendering.

## Tech Stack
- **Frontend**: Next.js, CodeMirror for code editing, WebSockets (Socket.io-client)
- **Backend**: Node.js, Express, Socket.io

## Installation

### Prerequisites
Ensure you have **Node.js** and **npm/yarn** installed on your system.

### Clone the repository
```sh
git clone https://github.com/Aditya-shou/Code-Forge-Live.git
cd Code-Forge-Live
```

### Install dependencies
#### Backend Setup
```sh
cd server
npm install
```

#### Frontend Setup
```sh
cd ../client
npm install
```

### Run the project
#### Start the backend server
```sh
cd server
node server.js
```

#### Start the frontend
```sh
cd ../client
npm run dev
```

### Usage
1. Open the application in your browser.
2. Enter a unique **Room ID** to create or join a session.
3. Share the **Room ID** with collaborators.
4. Start coding together in real-time!


---

Happy Coding! 🚀
