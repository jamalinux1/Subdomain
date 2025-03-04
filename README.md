# Subdomain Recon Automation
This script automates subdomain enumeration, live host detection, vulnerability scanning, and more for cybersecurity reconnaissance.

🚀 Features

Subdomain Enumeration: Uses Subfinder, ShodanX, Amass, Gobuster, crt.sh, AlienVault, URLScan, and Web Archive.

Live Host Detection: Filters active domains using httpx.

Port Scanning: Uses Naabu and Nmap.

Vulnerability Assessment: Runs Nikto and Nuclei.

Subdomain Takeover & Broken Link Hijacking: Detects takeovers with Subzy and broken links with SocialHunter.

Screenshot Capture: Uses Eyewitness for visual reconnaissance.

WAF Detection & Handling: Identifies and filters out WAF-protected subdomains.

Directory Fuzzing: Performs Dirsearch fuzzing on detected subdomains.

📥 Installation

Ensure you have the following tools installed:

sudo apt update && sudo apt install -y subfinder amass gobuster jq curl httpx naabu nmap nikto nuclei subzy socialhunter eyewitness dirsearch

🛠 Usage

Run the script by providing a target domain:

chmod +x subdomain_recon.sh
./subdomain_recon.sh target.com

📁 Output

Results are saved in a directory named recon_target.com. Use:

ls recon_target.com

⚠️ Disclaimer

This script is intended for legal security testing and research purposes only. Ensure you have permission before scanning any domain.

Happy Hunting! 🕵️‍♂️

