# MiniTalk

## 📜 Description
"MiniTalk" is a project that I made in my Cursus at 42School that demonstrates inter-process communication using Unix signals. It consists of a server and a client where the client sends messages to the server using signals. This project highlights the basics of signal handling and process synchronization in Unix.

## 🌟 Features
- Inter-process communication via Unix signals
- Simple client-server architecture
- Signal handling and management
- Process synchronization

## ⚙️ Installation

To clone and compile this project, follow these steps:

```bash
git clone https://github.com/your-username/MiniTalk.git
cd MiniTalk
make
```
## 🚀 Usage
First, run the server:
```
./server
```
The server will print its process ID (PID). Use this PID to send a message from the client:
```
./client <server_pid> "Your message"
```
Replace <server_pid> with the actual PID of the server and "Your message" with the message you want to send.
