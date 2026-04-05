# python-port-scanner
Basic Python port scanner for network security learning

## Overview
This project is a basic Python port scanner created to practice scripting and understand how open ports can expose network services.

## Purpose
The goal of this project was to learn how Python can be used in cybersecurity to automate simple network security tasks such as checking whether ports are open or closed on a target system.

## Tools Used
- Python
- Socket library

## Features
- Scans common TCP ports
- Identifies open and closed ports
- Helps demonstrate basic network reconnaissance concepts and security assessment techniques.

## Ports Scanned
- 21 (FTP)
- 22 (SSH)
- 23 (Telnet)
- 25 (SMTP)
- 53 (DNS)
- 80 (HTTP)
- 110 (POP3)
- 443 (HTTPS)

## How It Works
The script uses Python's socket library to attempt a connection to each selected port on a target IP address.  
If the connection succeeds, the port is reported as open. Otherwise, it is reported as closed.

## Example Use
py scanner.py

Enter target IP:
127.0.0.1

## What I Learned
- Basic Python scripting using the socket library  
- How TCP connections work in network communication  
- How port scanning supports network reconnaissance  
- Why open ports can increase a system’s attack surface  

## Ethical Use
This project was developed for learning purposes and tested in a controlled environment.
