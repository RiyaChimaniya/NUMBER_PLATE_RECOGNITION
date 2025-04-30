NUMBER_PLATE_RECOGNITION
Overview
This project implements a Java-based system for recognizing vehicle number plates. It includes a client-server architecture where the client sends data to the server for processing.

Features
Client-Server communication using sockets.
GUI for entering and displaying number plate information.
Real-time data exchange between client and server.
Getting Started
Prerequisites
Before you begin, ensure you have the following installed:

Java Development Kit (JDK) (version 8 or higher)
Apache NetBeans IDE (optional but recommended for GUI development)
Installation and Setup
1.Clone the repository:

bash

git clone https://github.com/RiyaChimaniya/NUMBER_PLATE_RECOGNITION.git
cd NUMBER_PLATE_RECOGNITION

2.Open the project in your IDE (NetBeans or any preferred Java IDE).

3Compile the source files:

bash

javac server.java client.java

Running the Project
Server

1.Run the server using:

bash

java server

2.The server listens on port 4000.

Client

>Run the client application:

bash

java client

>Use the GUI to input the number plate, and it will communicate with the server.
Dependencies
The project uses the following:

>Java Swing for GUI development.
>Java Networking (sockets) for client-server communication.
Configuration
>Ensure that both the client and server are running on the same system or network.
>Update the IP address and port in the client.java file if the server is hosted remotely:
Java
>
socket = new Socket("<server-ip>", 4000);
