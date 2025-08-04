# Multithreaded Chat App 🧵💬

A multithreaded chat application built in Python using sockets and threading.  
It supports real-time communication between multiple clients connected to a central server.

> Built from scratch to deepen my understanding of client-server architecture, network programming, and concurrency.

---

## 🛠 Features

- Real-time chat between multiple clients
- Server handles each client in a separate thread
- Clean shutdown on client disconnect
- Message broadcasting to all connected users
- (In Progress) GUI using Tkinter for user-friendly interface

---

## 📁 Project Structure

chat-app/
├── server.py # Runs the chat server
├── client.py # Runs a chat client
├── README.md # This file
├── .gitignore # Files and folders to exclude from Git
└── LICENSE # MIT License


---

## 🚀 Getting Started

### Requirements
- Python 3.7+

### Run the Server
```bash
python server.py

