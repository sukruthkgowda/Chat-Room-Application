
# Chat Room Application


## Overview

This project comprises two Python scripts - one for the chat server (serverType.py) and another for the chat client (clientType.py). The chat room enables real-time messaging between multiple clients and supports file sharing functionalities.

##  Server Setup
1. Open serverType.py in text editor.
2. Adjust the IP variable to the desired server IP address.
3. Run the script to start the chat server.



## Client Setup
1. Open clientType.py in a text editor.
2. Update the passkey variable with the server's passkey obtained during server setup.
3. Run the script to start the chat client.

## Usage
Upon connecting, clients can enter a username.
Type messages in the client terminal to send them to the chat room.

To send a file, use the "file:" prefix followed by the file path (e.g., file:example.txt).
Clients can disconnect by typing "exit" in the client terminal.

## Features
Real-time messaging with dynamic username updates.
File sharing capabilities with support for sending and receiving files.
Graceful handling of client disconnections and server shutdown.

## Dependencies
Python 3.x
Base64 library (included in Python standard library)

## Notes
Ensure firewall settings allow communication on the specified port (default: 5050).

The server's IP address and passkey must be shared with clients for connection.