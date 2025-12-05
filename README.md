# Java Chat Application

A simple real-time chat application built with Java Swing that allows two users to communicate over a local network using socket programming.

## Features

- **Real-time Messaging**: Instant message delivery between server and client
- **User-Friendly Interface**: Clean GUI built with Java Swing
- **Auto-Scroll**: Automatically scrolls to the latest message
- **Timestamp Display**: Shows the time each message was sent
- **Message Bubbles**: WhatsApp-style message display with right-aligned sent messages and left-aligned received messages
- **Enter Key Support**: Send messages by pressing Enter

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- IDE (Eclipse, IntelliJ IDEA, NetBeans) or command line with javac

## Project Structure

```
JavaApplication3/
├── src/
│   └── JavaApplication3/
│       ├── Server.java
│       └── client.java
└── icons/
    ├── download.png
    ├── images.jpg
    ├── super.jpeg
    ├── vid.png
    ├── voice.jpeg
    └── ver.png
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/java-chat-app.git
cd java-chat-app
```

2. Ensure all icon files are placed in the `icons/` directory at the project root

3. Compile the Java files:
```bash
javac src/JavaApplication3/Server.java
javac src/JavaApplication3/client.java
```

## Usage

### Running the Application

1. **Start the Server first:**
```bash
java -cp src JavaApplication3.Server
```
The server window will open at position (200, 20) on your screen with the name "AMAN".

2. **Start the Client:**
```bash
java -cp src JavaApplication3.client
```
The client window will open at position (800, 20) on your screen with the name "VROOO".

### Sending Messages

- Type your message in the text field at the bottom
- Click the "SEND" button or press Enter
- Messages appear on the right side (sent) in green bubbles
- Received messages appear on the left side

### Closing the Application

- Click the back arrow icon in the top-left corner of either window

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

Your Name - Aman Jain 

## Acknowledgments

- Java Swing documentation
- Socket programming tutorials
- WhatsApp UI inspiration
