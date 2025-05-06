# Java-Based Secure Chat and File Transfer System

A desktop-based chat application built using Java that enables secure real-time messaging and file transfer between users on a network. The system maintains a history of all messages exchanged and supports user authentication for private communication.


## Features

- **Secure Chat** – Real-time messaging with a structured message object.
- **File Transfer** – Upload and download files directly between users.
- **Message History** – Stores conversation history in an XML file and displays it in a GUI table.
- **User Login/Register** – Basic user authentication flow.
- **Simple GUI** – Easy-to-use interface built using Java Swing.
- **Client-Server Architecture** – Robust socket-based communication.


## Technology Used

- **Java SE (JDK 8 or higher)**
- **Java Swing** – for GUI components.
- **Java Sockets** – for networking and real-time communication.
- **XML** – for storing message history.
- **Multi-threading** – to handle simultaneous file transfers and chat.


## Project Structure

com/
├── server/           # Server logic
├── socket/           # Client-side networking and file transfer
├── ui/               # User Interface (Swing components)
├── utils/            # Helper methods (optional)
└── History.xml       # Stores message history


## Future Improvements

-Add encryption for chat messages.
-Implement user authentication via a database.
-Improve GUI with JavaFX or modern UI libraries
