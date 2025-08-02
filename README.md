# SingleThreaded-Webserver 🚦

A raw, minimalistic HTTP server built in Java — no frameworks, no fancy threads, just clean socket handling like it's supposed to be.

## 🧠 Why This Project?

Most tutorials jump straight to multithreaded chaos. This project slows it down — intentionally — to show how **one request at a time** can be a learning powerhouse. Think of it like learning to drive in first gear before speeding onto the highway.

## 🔍 What It Does

- Listens for client connections over TCP
- Serves simple HTTP responses
- Demonstrates how data flows between client and server
- Written entirely in Java using `java.net` and I/O streams

## 🧰 File Breakdown

| File            | Role                         |
|-----------------|------------------------------|
| `ClientSide.java` | Initiates request to the server |
| `ServerSide.java` | Accepts and handles incoming request |

## 🚀 How to Run

Compile:
```bash
javac ServerSide.java
javac ClientSide.java
