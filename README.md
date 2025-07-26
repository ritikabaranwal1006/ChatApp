# 💬 ChatApp

A simple Java-based chat application built using **Swing** and **Socket Programming** that enables real-time messaging between a client and a server on the same local network.

---

## ✨ Features
- 🖼️ Graphical User Interface (GUI) using Java Swing
- 🌐 Socket Programming using TCP
- 💬 Real-time message sending and receiving
- 🕒 Timestamp on each message
- ⚡ Lightweight and easy to run — no external libraries needed

---

## 🗂️ Project Structure
ChatApp/
├── Client.java       # Client-side chat application
├── Server.java       # Server-side message handler
├── icons/            # Folder containing images and icons
└── README.md         # Project documentation (this file)


---


```markdown
### ⚙️ How to Run

#### ✅ Prerequisites
- Java installed (JDK 8 or above)
- Any IDE (like VS Code, IntelliJ) or a command-line terminal

---

#### 🪜 Steps

##### 🔧 Step 1: Compile the Code
Open your terminal or command prompt in the `ChatApp` folder and run:
```bash
javac Server.java
javac Client.java
 Step 2: Start the Server
In the same terminal, run this command. Always start the server before the client.

Bash

java Server
🧑‍💻 Step 3: Start the Client (in a new terminal)
Open a new, separate terminal and run this command:

Bash

java Client
🗨️ Start Chatting!
You can now send and receive messages instantly within the same local network.
