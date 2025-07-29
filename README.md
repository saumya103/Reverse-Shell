# Reverse-Shell
The goal of this project is to create a reverse shell backdoor using Python. The reverse shell allows remote control of a compromised system by establishing a connection from the victim's machine (client) to an attacker's system (server).
This project consists of two Python scripts:
- 1. client.py – Runs on the target machine and initiates a reverse shell connection to the
attacker's machine.
- 2. server.py – Runs on the attacker's machine and listens for incoming connections,
allowing command execution and file transfers.


Once the connection is established, the attacker can execute system commands remotely,
upload/download files, and navigate through directories.
