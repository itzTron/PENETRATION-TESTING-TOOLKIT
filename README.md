# Penetration Testing Toolkit

## Overview
This is a CLI-based penetration testing toolkit built using Python. It includes multiple modules such as:
- **Port Scanner**
- **Brute-Force SSH Attack**
- **Password Generator**
- **Network Mapper**
- **Wi-Fi Deauthentication Attack**
- **Remote Vulnerability Scanner**

This toolkit is designed for ethical hacking and security testing purposes only. **Use it responsibly.**

## Features
- Interactive CLI menu
- Scans open ports on a target machine
- Maps devices on a network
- Generates secure random passwords
- Performs SSH brute-force attack (requires wordlist)
- Conducts Wi-Fi deauthentication attacks
- Runs remote vulnerability scans

## Prerequisites
Before running the script, install the required dependencies:
```bash
sudo apt update && sudo apt install -y python3 python3-pip nmap aircrack-ng
pip3 install scapy python-nmap paramiko
```

## Installation
Clone the repository from GitHub:
```bash
https://github.com/itzTron/PENETRATION-TESTING-TOOLKIT.git
```

## Usage
Make the script executable:
```bash
chmod +x pentest_toolkit.py
```

Run the script:
```bash
python3 pentest_toolkit.py
```

### Available Options in Menu:
1. **Scan open ports**: Enter a target IP to check for open ports.
2. **Map network devices**: Enter an IP range (e.g., `192.168.1.0/24`) to detect devices.
3. **Generate secure password**: Choose a password length to generate a random secure password.
4. **Perform remote vulnerability scan**: Enter a target IP to scan for vulnerabilities.
5. **Wi-Fi deauth attack**: Enter target MAC, AP MAC, and network interface.
6. **Exit**: Quit the program.

## Running as Root (If Required)
Some modules require root privileges. If you face permission issues, run:
```bash
sudo python3 pentest_toolkit.py
```

## Disclaimer
This tool is intended for educational and ethical security testing purposes only. Unauthorized use against networks or systems without permission is illegal. The developer is not responsible for any misuse.


