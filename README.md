# Peer‑to‑Peer Chat Application

## 📋 Team & Contributions

| Member Name   | Student ID | Contribution                                            |
|---------------|------------|---------------------------------------------------------|
| Jongmin Choi  | 203874794   | Server/client socket logic; connection management       |
|  Marzia Mehr  | 109951593   |   Developed server/client socket logic and connection management; implemented the help, myip, and myport commands, allowing users to view available commands, retrieve the host's IPv4 address, and identify the listening port number.  
Role Description:

help Command: Provides users with a list of all available commands, enhancing user interaction and clarity.

myip Command: Retrieves and displays the IPv4 address of the current process, facilitating easy network configuration and peer connection.

myport Command: Identifies and displays the port number on which the peer application is actively listening, crucial for establishing peer-to-peer connections.  |

<br>

## 🖥️ Prerequisites

- **Node.js ≥ 18.x**

## 🚀 Installation & Setup

1. Unzip `jongmin_choi_203874794.zip`.

## ▶️ Running

Open a terminal for each peer and run:

```bash
node chat.js <listening_port>
```

<br>

## 💬 Commands

| Command                           | Description                                        |
|-----------------------------------|----------------------------------------------------|
| `help`                            | Show all available commands                        |
| `myip`                            | Display this process’s IPv4 address                |
| `myport`                          | Display the listening port number                  |
| `connect <IP> <port>`             | Establish a new TCP connection to `<IP>:<port>`    |
| `list`                            | List all active connections (ID, IP address, port) |
| `terminate <connection id>`       | Close the specified connection by its ID           |
| `send <connection id> <message>`  | Send a message (max 100 chars) to the given ID     |
| `exit`                            | Terminate all connections and exit the program     |
