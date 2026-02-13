☕ SafeCoffee v2
Dynamic Network Defense by CavemanAI
SafeCoffee v2 is a proactive security application designed to protect users on public or untrusted Wi-Fi networks. While powered by the D-ARCai (Dynamic Advanced Research Concepts) engine, it is branded under CavemanAI to ensure that even non-technical users can participate in the "AI Revolution" by securing their digital perimeter with a single click.

🛡️ Core Features
DeepShield Monitoring: Constant surveillance of the ARP table and 802.11 frames to detect MITM (Man-in-the-Middle) attacks.

Heartbeat Verification: A background pulse that verifies the gateway's identity every 30 seconds to ensure your traffic isn't being rerouted.

Retaliatory Counter-Pulse: Automatically disrupts an attacker's connection using de-authentication frames if they attempt to spoof your gateway.

Terminal Panic Mode: An "emergency brake" that immediately shuts down your network interface to prevent data exfiltration.

High-Fidelity UI: A specialized PySide6 interface featuring the CavemanAI signature dark-mode aesthetic for high readability.

🛠️ Requirements & Environment
To maintain uniformity across the CavemanAI ecosystem, this tool requires Python 3.12 and the PySide6 GUI backbone.

🚀 Setup & Execution
Enter your CavemanAI Environment:
Ensure you are working within your established virtual environment on your persistent drive:

Install Scapy:
While PySide6 is likely already installed, you will need the Scapy engine:

Launch SafeCoffee:
Because the script utilizes raw sockets to protect your hardware, it must be run with sudo:

⚠️ Troubleshooting (Kali Linux Specifics)
Operating on a Kali Live USB often presents unique graphical and driver challenges. If you encounter issues, refer to the table below:

📜 Brand Philosophy: CavemanAI
"Smart tech for the modern hunter-gatherer."
