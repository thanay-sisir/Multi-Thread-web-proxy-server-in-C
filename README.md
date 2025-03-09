# Multi-Thread-web-proxy-server-in-C

This project implements a multi-threaded HTTP proxy server with an LRU (Least Recently Used) cache, designed to efficiently handle client web requests. Built in C, it acts as an intermediary between clients and remote servers, leveraging caching and concurrency to enhance performance. It serves as a valuable educational tool for learning threading, synchronization, and caching in operating systems.

METHODOLOGY
This project leverages a custom implementation to manage HTTP traffic, using a dataset of real-world web request patterns (simulated via client interactions). Key components include:
Threading: Utilizes POSIX threads (pthread) for concurrency.

Synchronization: Employs semaphores (sem_wait and sem_post) and mutex locks for thread safety.

Cache Management: Implements an LRU algorithm to store and evict responses based on a 200 MB total cache and 10 MB element limit.

Request Parsing: Parses HTTP GET requests using a custom parsing library (proxy_parse.c).

OUTPUTS:
STARTUP OUTPUT, CLIENT CONNECTION OUTPUT, CACHE MISS OUTPUT, CACHE HIT OUTPUT

![image](https://github.com/user-attachments/assets/98e29c87-f7e4-4c25-9c7e-85fa7086cc1d)


![image](https://github.com/user-attachments/assets/10153bb6-4d8f-44fe-95f5-555ed3f5baf7)

![image](https://github.com/user-attachments/assets/4d20dcdd-9543-4033-a154-dc8ee824e538)











