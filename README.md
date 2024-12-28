# Proxy-Web-Server-for-handling-Get-Requests


This project was created as part of a tutorial by **LovePreet Singh**.

## Overview
This project implements a Multi-Threaded Proxy Server with caching functionality. It acts as an intermediary between clients and servers, forwarding client requests to remote servers and caching responses to optimize repeated access to the same resources.

### Features
- Caching Mechanism: Stores server responses to reduce repeated requests for the same resource.
- Multi-Threading: Handles multiple client connections simultaneously using threads.
- Semaphore for Synchronization: Ensures safe access to shared resources like the cache.
- HTTP Error Handling: Sends appropriate HTTP error responses for various status codes (e.g., 400, 403, 404, etc.).
- HTTP Request Parsing: Parses incoming HTTP requests and forwards them to the remote server.
### Prerequisites
- C Compiler: GCC or any compatible compiler.
- Libraries:
- pthread: For multi-threading.
- semaphore.h: For synchronization.
- netinet/in.h and arpa/inet.h: For socket programming.
- unistd.h and fcntl.h: For file descriptors and operations.
