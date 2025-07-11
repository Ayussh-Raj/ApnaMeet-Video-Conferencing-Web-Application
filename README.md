# ApnaMeet-Video-Conferencing-Web-Application

ApnaMeet is a real-time video conferencing platform built with the **MERN stack**. It enables users to host or join meetings seamlessly using dynamic room links. The platform includes essential features like **screen sharing**, **meeting history tracking**, and **secure authentication**, delivering a robust virtual meeting experience.

## 🚀 Features

- 🔐 **Secure User Authentication**  
  Sign up and log in using protected credentials via **bcrypt hashing**.

- 🔗 **Dynamic Meeting Links**  
  Instantly generate unique room links for hosting or joining meetings.

- 📹 **Real-Time Video & Audio Calls**  
  Powered by **WebRTC** for peer-to-peer media connections.

- 🖥️ **Screen Sharing**  
  Share your screen with other participants during meetings.

- 📈 **Meeting History**  
  Keep track of previous meetings with session metadata.

- 💬 **Chat Functionality** *(optional enhancement)*  
  Real-time text messaging during calls via Socket.io.

- 🎨 **Responsive UI**  
  Built with **React** and **Material UI (MUI)** for modern design.

## 🛠️ Tech Stack

- **Frontend**: React.js, Material UI, WebRTC
- **Backend**: Node.js, Express.js, Socket.io
- **Authentication**: Bcrypt, JSON Web Tokens (JWT)
- **Database**: MongoDB
- **Other**: REST APIs, WebSockets

## 🧠 Learnings

- Implemented real-time WebRTC connections and signaling logic.
- Understood WebSocket (Socket.io) architecture for video and chat sync.
- Integrated secure backend authentication and session storage.

```bash
# Clone the repository
git clone https://github.com/Ayussh-Raj/apna-meet.git
cd apna-meet

# Install dependencies for client and server
cd client && npm install
cd ../server && npm install


