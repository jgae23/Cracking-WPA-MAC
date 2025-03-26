# Cracking-WPA-MAC  
This project explores vulnerabilities in WPA encryption, demonstrating how attackers can extract Wi-Fi passwords and MAC addresses using various cybersecurity tools. We conduct ethical research in a controlled environment to analyze network security flaws.
## Tools & Technologies  
- **Kali Linux**: A penetration testing OS that includes pre-installed security tools.  
- **Aircrack-ng**: Used to capture WPA/WPA2 4-way handshakes and crack Wi-Fi passwords.  
- **Wireshark**: Helps analyze captured packets and monitor network activity.  
- **Airodump-ng**: Scans and collects Wi-Fi network data, including MAC addresses.  
- **Python scripting**: Automates packet filtering, extracting MAC addresses, and sorting data.  
## Setup Guide  
1. Install Kali Linux on a VM or bootable USB.  
2. Install dependencies:  
   ```bash
   sudo apt update && sudo apt install aircrack-ng wireshark python3
3. Run Airodump-ng to capture network packets:
   ```bash
     airodump-ng wlan0mon
5. Use Python scripts in the scripts/ folder to process captured data
## Methodology  

### 1. Data Collection  
- Conduct active and passive network scanning (Airodump-ng).  
- Capture WPA/WPA2 handshakes using Aircrack-ng.  
- Extract MAC addresses from network traffic.  
- Monitor live network activity using Wireshark.  

### 2. Data Analysis  
- Use Python scripts to filter and organize MAC addresses.  
- Identify device manufacturers using OUI lookup.  
- Analyze unprotected packets for potential security risks.

## Expected Outcome  
- Successfully capture and analyze WPA handshake data.  
- Extract and process MAC addresses of connected devices.  
- Identify potential security risks in Wi-Fi networks.  
- Provide recommendations on improving wireless security.  

