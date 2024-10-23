Online Chat Application

This project implements a simple online chat application using Java socket programming. The application allows multiple users to connect to a central server, send messages, and receive messages from other users in real-time. 

* Features
- A dedicated server that handles multiple client connections.
- Clients can register with a unique name.
- Clients can send and receive messages instantly.
- Ensures usernames and messages are valid.
-Each client operates in a separate thread, allowing simultaneous communication.

* Components
- ChatServer: The server class that manages client connections and broadcasts messages.
- ChatClient: The client class that connects to the server, sends messages, and receives broadcasts.

* Requirements
- Java Development Kit (JDK) 8 or higher.
- A terminal or command prompt for running the server and client.

* How to Run the Application

 Step 1: Compile the Code
1. Open a terminal/command prompt.
2. Navigate to the project directory.
3. Compile the server and client code:
   javac server/ChatServer.java
   javac client/ChatClient.java

 Step 2: Start the Server
1. In the terminal, navigate to the server directory.
2. Run the server:
   java server.ChatServer
   
 Step 3: Start the Client
1. Open a new terminal window for each client.
2. Navigate to the client directory.
3. Run the client:
   java client.ChatClient
   
 Step 4: Connect and Chat
1. Follow the prompts to register your name.
2. Start sending messages. Type "bye" to exit the chat.

* Code Structure
- server/ChatServer.java: Contains the implementation of the chat server, including client handling and message broadcasting.
- client/ChatClient.java: Contains the client-side logic for connecting to the server and interacting with users.

 * Example Interaction
- Server Output:
    The chat server is now active
    rouhi with this ID 1 has joined the chat.
    
- Client Output:
    Register your name
    Please enter your name: rouhi
    Hello rouhi, you have this ID 1. You can start the conversation now.
    rouhi Connected to the chat.
    
This chat application demonstrates fundamental concepts of socket programming and concurrent user interaction. It provides a practical platform for understanding client-server architecture in network programming.
