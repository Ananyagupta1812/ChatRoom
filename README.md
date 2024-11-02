# Chatroom Application

A simple chatroom application built using Python’s `socket`, `tkinter`, and `threading` libraries. This project allows multiple clients to connect to a server, send and receive messages, and exit the chatroom gracefully.

## Features
- Multiple clients can join the chatroom.
- Clients can send messages to each other in real-time.
- GUI interface for user interaction.
- Users can leave the chatroom by typing "QUIT".

## Getting Started

### Prerequisites
Ensure you have Python 3.x installed. Additionally, this project uses `tkinter` for GUI, which is included by default in most Python installations.

### Installation
1. Clone the repository:
    git clone https://github.com/your-username/chatroom-application.git
    cd chatroom-application

2. Install required libraries:
    pip install tk. ---to install tkinter

### Usage

#### Starting the Server
To start the server, run:
    python Server.py <host>

#### Starting the Client
Open the Chat_app file in explorer and from the path open cmd. 
    In cmd type:
    python client.py 127.0.0.1 
to connect to the server and enter the room. 
