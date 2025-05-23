# Multithreaded Java Web Server

This project demonstrates a simple **web server-client architecture in Java**, showcasing both **single-threaded** and **multi-threaded** implementations.

---

## 📌 Features

- ✅ Multi-threaded Server that handles multiple client requests concurrently using threads.
- ✅ Single-threaded Server for comparison and understanding.
- ✅ Java `Socket` and `ServerSocket` APIs used for TCP-based communication.
- ✅ Simple use of functional interfaces like `Consumer` and `Runnable`.
- ✅ Client capable of spawning multiple threads to test server concurrency.

---


## 🚀 How to Run

### 1. Compile the project

Navigate to the `src/` directory in terminal:
```bash
cd path/to/web-server/src
javac MultiThreaded/*.java SingleThreaded/*.java
