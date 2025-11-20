# **TCP Web Server in C**

A minimal TCP web server written in C that serves an HTML file. This project is designed to help beginners understand the basics of socket programming, HTTP, and server architecture.

---

## **Features**
- Listens for incoming TCP connections on port 8080.
- Serves a static HTML file (`index.html`) to clients.
- Simple and easy-to-understand codebase.

---

## **Getting Started**

### **Prerequisites**
- GCC compiler
- Basic knowledge of C programming

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/Spectrae/http-server.git
   cd http-server
   ```
2. Compile the code:
   ```bash
   make
   ```
3. Run the server:
   ```bash
   make run
   ```


### **Usage**
- Open your browser and navigate to `http://localhost:8080`.
- You should see the content of `index.html` displayed.

---

## **Project Structure**
```
tcp-server/
├── index.html       # HTML file to serve
├── webserver.c      # C source code
└── Makefile         # For easy compilation
```
