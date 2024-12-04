 🚀 **Advanced Wireless Attack Suite**

This Bash script is a comprehensive tool for wireless penetration testing, focusing on scanning, attacking, and decrypting Wi-Fi networks. It automates common tasks in wireless security assessments and provides an interactive, user-friendly interface with vibrant visual elements.

---
 🔑 **Key Features:**

1. **Wi-Fi Scanning and Enumeration:**  
   Detect nearby wireless networks and capture handshakes for further analysis.

2. **Wi-Fi Deauthentication (DDoS) Attacks:**  
   Launch deauthentication attacks on targeted BSSIDs to disconnect clients and force handshake captures.

3. **Decrypt CAP Files:**  
   Use brute-force attacks with a password dictionary to crack captured handshakes using `aircrack-ng`.

4. **User-Friendly Interface:**  
   Enjoy colorful ASCII art and enhanced user prompts, powered by `toilet`, `lolcat`, and `cowsay`.

---

🛠️ **Requirements:**

- **Operating System:** Linux (tested on Kali Linux)
- **Dependencies:**  
   - `aircrack-ng`  
   - `toilet`  
   - `lolcat`  
   - `cowsay`  
   
   Install dependencies using:
   ```bash
   sudo apt-get install aircrack-ng toilet lolcat cowsay figlet
   ```

---
 📋 **Usage Instructions:**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/wifi-attack.git
   cd wifi-attack-suite
   ```

2. **Make the script executable:**
   ```bash
   chmod +x wifi_attack.sh
   ```

3. **Run the script with root privileges:**
   ```bash
   sudo ./wifi_attack.sh
   ```

---
**Example Workflow:**

1. **Choose an attack method:**
   - **[1] Wi-Fi Scanning and Enumeration:** Capture handshakes from target networks.
   - **[2] Wi-Fi DDoS Attack:** Launch a deauthentication attack on the specified BSSID.
   - **[3] Decrypt CAP Files:** Crack Wi-Fi passwords using a dictionary attack.

2. **Follow the prompts:**  
   Enter the network interface, BSSID, and additional details as required.

3. **Monitor progress:**  
   Outputs are displayed in real-time, and results are saved in the current directory.

---

 🧠 **Important Notes:**

- Ensure you run the script as **root**.
- Use this tool **responsibly and legally**. Unauthorized access to networks is illegal.
- Recommended for educational purposes and authorized penetration testing only.

---  

--- 
⚠️ **Disclaimer:** Use responsibly and ethically. Unauthorized use for malicious purposes is strictly prohibited.
