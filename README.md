To run SecAletheia on Kali Linux, follow these steps:

Clone the repository:

git clone https://github.com/vegetzo1500/SecAletheia.git
cd SecAletheia

Install Python dependencies:

sudo apt update
sudo apt install python3-pip -y
pip3 install requests

Install required pentesting tools:

sudo apt install nmap gobuster hydra nikto sqlmap whatweb metasploit-framework -y

Run the application:

python3 secaletheia.py

Notes:

Python 3.8 or later is required.

An internet connection and OpenAI API key are needed for the AI summary feature.

Use this tool only on authorized targets where you have explicit permission to perform security testing.

