# ✨ Streamify: Fullstack Language Exchange & Video Call App ✨

[![Deploy](https://img.shields.io/badge/View-Live%20Demo-brightgreen)](https://video-call-chat-app-mq68.onrender.com/)
[![Repo](https://img.shields.io/badge/GitHub-Repository-black)](https://github.com/milesmoralis2411/video_call_chat_app)

<br>

<p align="center">
  <a href="https://drive.google.com/file/d/12A0UIRZhJBWpd8nhM47g_j_yENjr6A8N/view?usp=drive_link" target="_blank">
    <img src="https://img.shields.io/badge/Watch_Full_App_Demo-Video_Link-blue.svg?style=for-the-badge&logo=google-drive" alt="Watch the Full App Demo on Google Drive" height="40">
  </a>
</p>

## 🚀 About The Project

**Streamify** is a full-featured, real-time video call and chat application designed to connect language learners from around the world. It's built with the MERN stack (MongoDB, Express, React, Node.js) and powered by the Stream API for robust, scalable chat and video functionalities.

The platform allows users to find language exchange partners, send friend requests, chat in real-time, and launch high-quality video calls directly from the app. It features a secure JWT authentication system, a modern responsive UI, and a clean, intuitive user experience.

### Deployed Link

**[https://video-call-chat-app-mq68.onrender.com/](https://video-call-chat-app-mq68.onrender.com/)**

---

## 📋 How It Works: The User Flow

The application provides a seamless experience from finding a partner to having a conversation.

1.  **Authentication**: A user first visits the site and is presented with a **Login** or **Sign Up** page.
2.  **Sign Up & Login**: New users can register, and existing users can log in. The backend validates credentials and returns a **JWT (JSON Web Token)** for session management.
3.  **Authorization**: This JWT is used to protect all core application routes, ensuring only logged-in users can access the dashboard, chats, and calls.
4.  **Find Learners**: After logging in, the user lands on the main dashboard. Here, they can browse profiles of "New Learners," clearly seeing each user's **Native Language** and **Learning Language**.
5.  **Friend Request System**: Users can send friend requests to potential partners.
6.  **Notifications**: The "Notifications" tab alerts users when their friend requests have been accepted, turning a "New Learner" into a "Friend."
7.  **Real-time Chat**: Users can open a chat window with their connected friends to send text messages and image attachments in real-time.
8.  **Initiate Video Call**: From any chat window, a user can instantly start a 1-on-1 video call by sending a unique, secure join link directly into the chat.
9.  **Video Call**: Both users can join the video call room, which includes controls for muting the mic, toggling the camera, sharing their screen, and ending the call.

---

## 🌟 Key Features

This project includes a wide range of modern, real-time features.

### Core Platform Features
* **Language Learner Matching**: The primary dashboard allows users to discover new language partners based on their native and learning language preferences.
* **Friend Request System**: A complete social system to send, receive, and accept friend requests.
* **Notification Center**: A dedicated page to alert users of new connections and other important updates.
* **Secure JWT Authentication**: Full user login and registration flow with hashed passwords (`bcrypt`) and protected routes.

### Real-time Chat (via Stream)
* **1-on-1 & Group Chats**: Seamlessly create and manage chat channels with friends.
* **Image Attachments**: Share images directly in the chat window.
* **Video Call Integration**: Start a video call and automatically send the secure join link into the chat.
* **Modern Chat UI**: Features include typing indicators, emoji reactions, and read receipts.

### Real-time Video & Voice Calls (via Stream)
* **High-Quality Video**: Crisp and clear 1-on-1 and group video calling.
* **Full Call Controls**: Includes buttons to toggle mic/camera, screen share, view participants, and end the call.
* **Secure & Private**: Video call rooms are accessible only via a unique, generated link.

### Modern UI & UX
* **32 Unique UI Themes**: Users can personalize their experience with a wide variety of themes (including light and dark modes).
* **Fully Responsive Design**: A beautiful and functional layout on all devices, from mobile to desktop, built with **TailwindCSS**.
* **Optimistic UI Updates**: Using **TanStack Query (React Query)**, the UI updates instantly while data is fetched in the background, providing a fast and smooth user experience.
* **Global State Management**: Lightweight state management with **Zustand** to handle user auth state and theme preferences.

---

## ✨ Application Screenshots

I've used your exact filenames and placed them based on their likely content.

### 1. Friends Dashboard & Language Matching
Find new partners based on the languages they speak and want to learn.
<img src="./readme-assets/Screenshot 2025-10-24 115137.png" alt="Friends Dashboard & Language Matching" width="700"/>

### 2. Notification Center
Get updates when users accept your friend requests.
<img src="./readme-assets/Screenshot 2025-10-24 115036.png" alt="Notification Center" width="700"/>

### 3. Real-time Chat Window
Chat with friends, send images, and start a video call.
<img src="./readme-assets/Screenshot 2025-10-24 114939.png" alt="Real-time Chat Window" width="700"/>

### 4. Video Call in Progress
Join a high-quality video call with full controls for mic, camera, and screen sharing.
<img src="readme-assets/Screenshot 2025-10-24 114905.png" alt="Video Call in Progress" width="700"/>

---

## 🛠️ Tech Stack

This project is built with a modern, scalable tech stack.

### Frontend
* **React.js**: A JavaScript library for building user interfaces.
* **TailwindCSS**: A utility-first CSS framework for rapid UI development.
* **TanStack Query (React Query)**: For server-state management (fetching, caching).
* **Zustand**: For client-state management (global state).
* **Stream SDK**: For integrating chat and video call APIs.

### Backend
* **Node.js**: A JavaScript runtime environment.
* **Express.js**: A minimal and flexible Node.js web application framework.
* **MongoDB**: A NoSQL database for storing user and chat data.
* **Mongoose**: An ODM (Object Data Modeling) library for MongoDB and Node.js.
* **Stream API**: Manages all real-time chat and video logic on the backend.
* **JWT (JSON Web Tokens)**: For secure user authentication.
* **Bcrypt.js**: For hashing user passwords.
