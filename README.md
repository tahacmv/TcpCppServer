# C++ Client-Server Chat Application

This project is a simple TCP client-server chat application written in C++. The server listens for connections from clients, accepts messages from connected clients, and echoes these messages back to the client. This example demonstrates basic TCP socket programming concepts, including creating, binding, listening, and accepting sockets on the server side, and connecting, sending, and receiving data on the client side.

## System Requirements

- Windows operating system
- Visual Studio or a similar IDE that supports C++
- Windows SDK for Windows 10 or newer
- C++17 standard or newer

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you compile and run the client-server application, make sure you have the following installed:
- Microsoft Visual Studio (2017 or later recommended)
- Windows 10 SDK

### Compiling the Project

1. **Open Visual Studio.**
2. **Create a new project** and select a Console App for C++.
3. **Add the provided server and client code** to two separate projects within your solution.
    - For the server code, copy the first block of code into a new file, e.g., `server.cpp`.
    - For the client code, copy the second block of code into a new file, e.g., `client.cpp`.
4. **Set up your project to use the Windows Sockets library (`ws2_32.lib`).**
    - Right-click on the project in the Solution Explorer > Properties.
    - Navigate to Linker > Input > Additional Dependencies.
    - Add `ws2_32.lib` to the list and apply the changes.

### Running the Application

1. **Start the server application first** by running the `server.cpp` project. It will listen for incoming connections on port 54000.
2. **Run the client application** by executing the `client.cpp` project. Make sure to start the client after the server is already listening.
3. **Follow the on-screen instructions** on the client application to send messages to the server.

## Example Usage

Once both applications are running, you can type messages into the client's console window. These messages will be sent to the server, which then echoes them back to the client, displaying them on the client's console.

- Client: Type a message and press Enter.
- Server: Automatically echoes the received message back to the client.
- Client: Receives and displays the echoed message.

## Closing the Applications

To close the applications, simply enter an empty message from the client or close the console windows.

## Authors

- MOTASSIM AHMED TAHA