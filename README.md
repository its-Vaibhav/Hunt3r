# Hunt3r - An Automatic Pentesting Tool
Hunt3r is a modular, automated penetration testing framework that aims to improve cybersecurity by simplifying vulnerability detection and mitigation. The framework, written in Python, makes use of cutting-edge security technologies to perform complete network, application, and system evaluations. Hunt3r automates critical penetration testing processes, saving manual labor and allowing for continuous monitoring to keep ahead of developing vulnerabilities.

# Installation:
git clone https://github.com/khare404/Hunt3r.git

cd hunt3r

chmod +x install.sh

sudo ./install.sh

Run the tool:

"sudo python3 hunter.py"

# Features:
Automated Scanning: Hunt3r automates the process of scanning web applications, making it efficient and thorough.

Information Gathering: Integration with tools such as sublist3r, whois, dnsrecon ensures detailed and accurate information collection.

Vulnerability Detection: Identifies and analyzes vulnerabilities present in the target web application.

Strong Encryption: Applies robust encryption to the generated report files to ensure secure handling and storage of sensitive information.

This tool is specifically tailored for web applications and encompasses the following stages:

# Reconnaissance:
Gather preliminary information about the target web application.

Utilize tools like whois,dnsrecon,sublist3r to collect data such as email addresses, subdomains, and other relevant metadata.

# Scanning:
Perform automated scanning to identify potential vulnerabilities.

Employ tools like nmap module to scan for known vulnerabilitis and misconfigurations.

# Exploiting:
Determine the presence of vulnerabilities in the web application.

Execute scripts to potentially exploit these vulnerabilities in a controlled, ethical manner to assess their impact.

# Reporting:
Compile the findings into a comprehensive report.

Encrypt it to securely store the file
