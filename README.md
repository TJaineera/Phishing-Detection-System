Phishing Detection System

Phishing Detection System Overview:
A real-time phishing detection tool built using Python that analyzes websites, URLs, and SSL certificates to identify possible phishing attempts. The tool helps users verify the security of web pages through both console-based and GUI-based interfaces.
Features:
- Real-Time Phishing Detection – Checks websites for suspicious patterns
- SSL Certificate Analysis – Validates certificate authenticity and expiry
- URL Feature Extraction – Examines domain structure, HTTPS presence, and symbols
- IP and Subdomain Checks – Detects excessive subdomains or direct IP usage
- GUI Interface – Built using PySimpleGUI for ease of use
- Instant Results Popup – Displays phishing vs. secure indicators visually
How It Works:
1. The user enters a URL into the interface.
2. The system performs several checks:
- Validates the SSL certificate
- Extracts URL features
- Verifies domain reputation and IP usage
- Flags phishing indicators
3. Displays a final report — whether the site appears secure or phishing.
Tech Stack:
- Language: Python 3.10+
- UI: PySimpleGUI
- Networking: socket, ssl, dns.resolver
- Web Requests: requests
- Domain Info: whois
- Data Validation: regex, urllib.parse
- Visualization: Popup windows for status reporting
Installation & Setup:
1. Clone this repository:
git clone https://github.com/TJaineera/Phishing-Detection-System.git
cd Phishing-Detection-System
2. Install required libraries:
pip install -r Requirements.txt
3. Run the tool:
python Main.py
or
python Program.py
Usage Example:
Step 1: Launch the app (A window appears prompting you to enter a URL.)
Step 2: Enter a website link (Example: https://example.com)
Step 3: View Results (Secure or Phishing results displayed with popups)
Sample Screenshots:
- Secure Site: Analysis Report - No Phishing found.PNG
- Phishing Found: Analysis Report - phishing found.PNG
- SSL Valid: SSL certificate checking.PNG
- SSL Invalid: SSL certificate not found.PNG
Requirements:
requests, ssl, socket, dns.resolver, datetime, re, whois, ipaddress, PySimpleGUI, urllib.parse

Author:
Twinkle Jaineera

GitHub: https://github.com/TJaineera

Future Enhancements:
- Add ML-based phishing detection
- Integrate domain reputation API (VirusTotal / PhishTank)
- Include browser extension support
- Export reports as PDF
  
License:
This project is licensed under the MIT License.
