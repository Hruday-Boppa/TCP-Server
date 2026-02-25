# Simple TCP Client-Server in C

This project contains a basic TCP server and client written in C using the POSIX socket API.

## Files

- `server.c` — TCP server that listens on port 8080
- `client.c` — TCP client that connects to the server

---

## How to Compile

```bash
gcc server.c -o server
gcc client.c -o client
