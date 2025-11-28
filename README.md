# 📘 Simple Python Port Scanner

A beginner‑friendly **TCP port scanner** written in Python using the built‑in `socket` module.  
This script scans the first **1024 ports** of a target IP and prints all **open ports**.

Perfect for learning basic networking and cybersecurity concepts.



## 🚀 Features

- Scans TCP ports from **1 → 1024**
- Uses `socket.connect_ex()` to test each port  
- Fast (uses a small timeout to speed up scanning)  
- No external libraries required  
- Works on Windows, Linux, and macOS  



## 🧠 How It Works

1. User enters a target IP.
2. The script loops through ports **1 to 1024**.
3. For each port:
   - Creates a socket  
   - Sets a timeout  
   - Tries to connect to the current port  
   - If connection succeeds → **port is OPEN**  
   - Closes the socket  
4. Prints all open ports found.



# ⚠️ Legal Disclaimer

This tool is for educational and testing purposes only.

Only scan:

✔ Your own devices
✔ Your own local network
✔ Systems you have explicit permission to test

Unauthorized port scanning can be illegal.


