<p align="center">
  <img src="logo/omegon-logo.png" width="500" alt="Omegon Logo">
</p>

<h3 align="center">A reconnaissance tool to scan a website for vulnerabilities</h3>

<br>
<br>

## ⚠️Note: disclaimer
- **The Scanning Engine:** All vulnerability scanning, template matching, and core engine functionality are powered by [Nuclei](https://github.com/projectdiscovery/nuclei).
- **Ownership:** I do not own Nuclei or the Nuclei templates. This project simply provides the "glue" and automation logic surrounding the engine. Please support the original creators at [ProjectDiscovery](https://projectdiscovery.io/).
- **Authorization:** I designed this script to be executed only against systems you own or where you have explicit, written permission to test.
- **Liability:** I am not responsible for any misuse, damage, or legal consequences caused by this tool. You use this software at your own risk.
- **Compliance:** Using this tool to "attack" targets without prior mutual consent is illegal. It is your responsibility as the user to obey all local and international laws.

<br>  

## 🛠️Technologies
- `Python`
- `Bash`
- `Nuclei`

<br>

## ✨Features
- **Automated Reconnaissance:** Rapidly identifies web assets and active services.
- **Template-Based Scanning:** Leverages the powerful Nuclei engine for industry-standard vulnerability detection.
- **Modular Logic:** Optimized using a hybrid of Python and Bash for maximum execution speed.
  
<br>

## ⚙️The Process
My inspiration for Omegon came from the Dutch Government Bug Bounty program. I was highly motivated to identify vulnerabilities in critical infrastructure, but I realized that manual testing was too slow to keep up with the scale of modern web environments. I needed a way to scan for weaknesses at high speed without sacrificing accuracy.

<br>

## 📋Prerequisites
- `Kali machine` (preferably latest version) with the following tools/software:
   - `Python` 
   - `Nuclei`
- `Working network connection`

<br>

## 🚀Running the Project

### Step 1: Installation & Dependency Check
- Update the system: `sudo apt update && sudo apt upgrade -y`
- Install Python: `sudo apt install python3 python3-pip -y`
- Install Nuclei: `sudo apt install nuclei -y && nuclei -ut`

<p align="left">
  <img src="assets/step 1.gif" alt="Omegon Demo1" width="600">
</p>
