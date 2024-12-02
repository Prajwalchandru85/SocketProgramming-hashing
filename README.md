# SocketProgramming-hashing
 # Client-Server Hashing Application

This project implements a simple client-server application where the client sends a message to the server, and the server computes a hash of the message using a custom hash function (DJB2 algorithm) or SHA-256, then sends the hash back to the client.

## Features
- Client-Server communication using TCP sockets.
- Message hashing using SHA-256.
- Verifies data integrity by comparing the computed hash with the received hash.

## How to Use
1. **Run the Server**  
   Start the server script:  
   ```bash
   python server.py

