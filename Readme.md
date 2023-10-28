# UDP Chat Application

The UDP Chat Application is a simple chat program that allows users to send and receive messages over a local network using the User Datagram Protocol (UDP). This project consists of two Java files: `UDPClient.java` for the client-side and `UDPServer.java` for the server-side.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Error Handling](#error-handling)
- [License](#license)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

## Installation

1. Install java 15+ version.
2. clone project.
3. Run locally

### Server

1. Compile and run `UDPServer.java` on the machine that will act as the server. The server listens on port 12345 by default.
2. Ensure that the server is running and waiting for incoming client connections.

### Client

1. Compile and run `UDPClient.java` on each client machine.
2. When prompted, enter a unique username to identify yourself.
3. You can now send and receive messages with other connected clients on the network.

## Usage

Once the server and clients are set up, you can use the UDP Chat Application as follows:

- After entering a username, you can start sending and receiving messages in the chat window.
- To send a message, type your message in the input text field and press the "Send" button or press Enter.
- To quit the chat, type "/quit" and press "Send." This will remove you from the chat and close the client application.

## Error Handling

- If the server or any client encounters an error during execution, error messages will be printed to the console, allowing you to diagnose and resolve issues.
- The client and server applications handle common exceptions and provide feedback in case of problems.

## License

This project is released under the [MIT License](LICENSE).

## Contributing

Contributions to this project are welcome. If you would like to contribute, please follow these guidelines:

1. Fork the project.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Submit a pull request.

## Acknowledgments

- This project is based on Java and the User Datagram Protocol (UDP).
