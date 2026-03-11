# Network-scanning-lab
Tools used(Nmap,scripts,command prompt) 
# Network Reconnaissance & Vulnerability Scanning Lab

## Project Overview
This project demonstrates my first cybersecurity hands-on lab using **Nmap**, a network scanning tool. The goal was to learn network reconnaissance, identify open ports, detect running services, and perform vulnerability scanning on an authorized test host.

## Tools Used
- **Nmap** – network scanning and vulnerability detection
- **Command Prompt** (Windows) – running Nmap commands
- Text editor (Notepad) – viewing and saving scan results

## Steps Performed
1. **Basic Scan**
- Command: `nmap scanme.nmap.org`
- Purpose: Identify open ports and running services on the test host
- Output saved in `InitialPortScan.txt`
- Screenshot: `screenshots/01_BasicScan.png`

2. **Host Discovery / Network Scan**
- Command: `nmap -sn 192.168.1.0/24`
- Purpose: Identify active devices on my local network
- Screenshot: `screenshots/03_HostDiscovery.png`

3. **Vulnerability Scan**
- Command: `nmap --script vuln scanme.nmap.org`
- Purpose: Detect potential vulnerabilities using Nmap scripting engine
- Output saved in `VulnerabilityScan.txt`
- Screenshot: `screenshots/02_VulnScan.png`

## Key Findings
- Open ports were identified on the test host (SSH, HTTP, etc.)
- Services and their versions were detected using Nmap
- Vulnerability scan highlighted areas for potential security improvement (on authorized test host)
- Active hosts were identified on my local network, demonstrating host discovery

## Notes
- This project was performed on **authorized test hosts only** (`scanme.nmap.org`)
- All scans are safe and for educational purposes

## How to Run
1. Open **Command Prompt**
2. Navigate to the folder containing Nmap
3. Run any of the commands listed above
4. View results in `.txt` files or screenshots
