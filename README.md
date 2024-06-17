# MiniTalk

## 📜 Description
"MiniTalk" is a project that I made in my Cursus at 42School that demonstrates inter-process communication using Unix signals. It consists of a server and a client where the client sends messages to the server using signals. This project highlights the basics of signal handling and process synchronization in Unix.

#### ⭐ My 42 score for this project:
![image](https://github.com/yvann-ba/MiniTalk/assets/97234242/29d8e0fb-d3b3-4789-8731-d9a3a8b653b6)

#### 📄 Official 42 School Subject:
https://github.com/rphlr/42-Subjects/blob/main/common-core/minitalk/en.subject.pdf

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
