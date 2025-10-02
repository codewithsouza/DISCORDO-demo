📞 Discordo - Real-Time Communication Platform Demo
Stack: Django · PostgreSQL · Redis · Django Channels · WebRTC · Vanilla JS
A Discord-inspired real-time communication platform built as a portfolio project. Features P2P video/audio calls, instant messaging, friend management, and real-time notifications via WebRTC + WebSocket.

🎯 Features

👤 User Authentication - Login, registration, avatars, and online status
👥 Friend System - Add friends, accept/decline requests, mutual friends
📞 P2P Calls - Video/audio calling with media controls and call history
💬 Real-Time Messaging - Instant chat with persistent history
🎨 Modern UI - Discord-inspired responsive interface
🌐 Live Notifications - Real-time alerts for calls, messages, and requests


🖼️ Screenshots
🔐 Authentication
<table>
  <tr>
    <td><img src="Discordo-DEMO/login.png" alt="Login Screen" width="400"/><br/><b>Login</b></td>
    <td><img src="Discordo-DEMO/Cadastro.png" alt="Registration Screen" width="400"/><br/><b>Registration</b></td>
  </tr>
</table>
🏠 Dashboard & Profile
<table>
  <tr>
    <td><img src="Discordo-DEMO/dashboard.png" alt="Dashboard" width="400"/><br/><b>Main Dashboard</b></td>
    <td><img src="Discordo-DEMO/perfil.png" alt="User Profile" width="400"/><br/><b>User Profile</b></td>
  </tr>
</table>
📞 P2P Video Calls
<table>
  <tr>
    <td><img src="Discordo-DEMO/ligação fazendo.png" alt="Outgoing Call" width="400"/><br/><b>Initiating Call</b></td>
    <td><img src="Discordo-DEMO/ligação recebendo.png" alt="Incoming Call" width="400"/><br/><b>Receiving Call</b></td>
  </tr>
  <tr>
    <td colspan="2" align="center"><img src="Discordo-DEMO/call.png" alt="Active Call" width="400"/><br/><b>Active Call</b></td>
  </tr>
</table>
💬 Real-Time Messaging
<table>
  <tr>
    <td align="center"><img src="Discordo-DEMO/chat.png" alt="Chat Interface" width="400"/><br/><b>Chat Interface</b></td>
  </tr>
</table>

🛠️ Tech Stack

Backend: Django, Django REST Framework, Django Channels
Frontend: WebRTC, HTML5, CSS3, Vanilla JavaScript, Bootstrap
Database: PostgreSQL (production) / SQLite (development)
Infrastructure: Redis, Docker, Railway


🏗️ Architecture
Frontend (WebRTC) ⇆ Django API (REST) ⇆ WebSocket (Channels)
         │                    │                   │
         └──────── PostgreSQL ┘                   │
                           └────────── Redis ─────┘

🚀 Live Demo

Note: This is a portfolio demonstration project showcasing full-stack development skills including real-time communication, WebRTC implementation, and modern web technologies.

