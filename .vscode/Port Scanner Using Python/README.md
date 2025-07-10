# 🔎 Project 4: Port Scanner Using Python

## 📌 Problem Statement
Network ports act as gateways for services, and improperly secured open ports can expose systems to security threats. Identifying open ports helps in assessing vulnerabilities and tightening access controls.

## 🎯 Objective
Develop a command-line Python script that scans specified IP addresses or domain names for open ports. This tool is intended for educational use and basic security awareness testing.

## 🛠️ Requirements

- Python 3.x  
- Built-in `socket` module (for network connection handling)  
- Built-in `threading` module (for concurrent scanning)  
- Optional: `argparse` for CLI argument parsing

## ⚙️ Installation Steps

1. Clone or download the project repository.
2. Open a terminal and navigate to the project folder.
3. Ensure Python is installed (`python --version`).
4. No external libraries are required—standard Python modules only.

## 🚀 How to Run

1. Run the script using:

   ```bash
   python port_scanner.py
- Enter the IP address or domain name to scan.
- The script will loop through a set range of ports and list the ones that are open.
## 📂 Features
- Scans ports using TCP socket connection
- Multi-threaded approach for faster scanning
- Customizable port range
- Displays open ports and associated services (if detected)
## ✅ Expected OutcomeUsers will:
- Identify open ports on target IP/domain
- Understand basic socket programming
- Learn how multi-threading improves scanning efficiency
- Gain foundational knowledge in network security assessment
## 📚 Further Learning
- Implement service fingerprinting using banner grabbing
- Create logs or reports for scanned results
- Explore advanced scanners like Nmap or integrate with scanning APIs
- Add exception handling and performance tracking
⚠️ DisclaimerUse this scanner ethically. Only scan devices you own or have explicit permission to test. Unauthorized scanning can violate laws and network policies.Built to explore, not exploit ⚙
