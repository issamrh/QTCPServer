# QTCPServer
Qt TCP Server

A small TCP server built with Qt and C++ to manage multiple client connections. 
The server lets you see connected clients, read messages from them, and send messages 
to either all clients or just one.

Features:

- Start a server on port 8888 (or any port you choose).
- Handle multiple clients at the same time.
- Display messages from clients in a simple GUI.
- Send messages to all clients or select one from a dropdown.
- Live updates when clients connect.

How to Use:

1. Open the project in Qt Creator and build it.
2. Run the server—it will start listening on port 8888.
3. Connect clients using any TCP client.
4. Use the GUI to see messages and send replies.

Notes:

- Built with Qt 5.x and C++11.
- Uses QTcpServer and QTcpSocket for networking.
- Keeps track of clients using a QList of sockets.
