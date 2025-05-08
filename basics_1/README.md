# Networking Basics #1

## Project Overview
**Level:** Amateur  
**Author:** Sylvain Kalache  
**Weight:** 1  

This project focuses on basic networking concepts, including essential networking commands and the understanding of common networking terms. You will learn to explain fundamental networking topics without relying on external sources.

---

### Learning Objectives
By the end of this project, you should be able to explain the following concepts:

#### General Networking Concepts
- **What is localhost/127.0.0.1?**  
  Localhost is a hostname that refers to the local machine. The IP address `127.0.0.1` is the loopback address, commonly used for testing and development.

- **What is 0.0.0.0?**  
  The IP address `0.0.0.0` is a non-routable meta-address used to specify an invalid, unknown, or non-applicable target. It often indicates that a server is listening on all available IP addresses.

- **What is /etc/hosts?**  
  The `/etc/hosts` file is used to map IP addresses to hostnames. It is a simple way to configure local name resolution.

- **How to display your machine’s active network interfaces?**  
  You can use the command `ifconfig` or `ip addr` to list the active network interfaces on your system.

---

### Commands and Tools
The following commands are essential for this project:

- **ifconfig:** Displays network interfaces and their configurations.  
- **telnet:** A tool used to communicate with remote devices via TCP.  
- **nc (netcat):** A versatile networking utility for reading and writing data across networks.  
- **cut:** Used to extract sections from each line of files.  

---

### Command Usage Examples

#### Display Active Network Interfaces
```bash
ifconfig
