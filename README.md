Advanced Wireless Attack Suite

This script is an advanced wireless penetration testing tool designed for capturing Wi-Fi handshakes, performing DDOS attacks, and decrypting captured `.cap` files. It leverages powerful tools like `airmon-ng`, `airodump-ng`, `aireplay-ng`, and `aircrack-ng` to carry out various attacks on wireless networks.

**Features:**
- **Wi-Fi Offensive Scanning and Enumeration**: Scans and lists available Wi-Fi networks in your vicinity. You can choose a target network and capture the handshake for further analysis.
- **Wi-Fi DDOS Attack**: Uses `aireplay-ng` to perform a deauthentication (DDOS) attack on the target BSSID to speed up handshake capture.
- **Cap File Decryption**: Cracks captured Wi-Fi handshakes using a wordlist for password recovery with `aircrack-ng`.
- **Easy-to-Use Interface**: A menu-driven interface makes it simple to choose different attack methods and interact with the script.

**Usage:**
1. **Install Dependencies**: Make sure you have `airmon-ng`, `airodump-ng`, `aireplay-ng`, and `aircrack-ng` installed on your system.
2. **Run as Root**: This script requires root privileges to run. Use `sudo` to run the script.
3. **Select Attack Method**: After starting the script, choose from options like scanning for networks, performing DDOS attacks, or decrypting `.cap` files.
4. **Monitor Mode**: If monitor mode isn't already active, the script will enable it automatically.

**Instructions:**
1. To scan for networks and capture handshakes, choose option `[1] Wi-Fi Offensive Scanning and Enumeration`.
2. For initiating a DDOS attack to speed up handshake capture, choose `[2] Wi-Fi DDOS Attack`. 
3. To crack captured handshakes, choose `[3] Decrypt Cap Files`.

**Disclaimer:**
This tool is intended for educational purposes and authorized penetration testing only. Using this script for illegal activities is strictly prohibited. Ensure you have explicit permission before testing any network.

