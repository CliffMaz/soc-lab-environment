# soc-lab-environment
This contains:

  Lab setup
  Network diagram
  Domain
  Domain setup
  Splunk installation
  Troubleshooting
  Screenshots
  Architecture explanation

🛡️ Active Directory Domain Deployment & Configuration
📌 Overview
Designed and deployed a Windows Active Directory lab environment to simulate a corporate network infrastructure.
🏗️ Environment
• Windows Server (Domain Controller)192.168.10.10
• Windows 10 Client(DHCP from server)
• Windows Server (Splunk) 192.168.10.20
• Internal Virtual Network (SOC_LAN)
• pfsense firewall/router(192.168.10.1)
• Kali linux(Attackers machine)
• DNS configured on DC
⚙️ Key Tasks
• Installed Active Directory Domain Services (AD DS)
• Promoted server to Domain Controller
• Configured DNS for domain resolution
• Created domain users
• Joined Windows client to domain
• Verified forward and reverse DNS resolution
• Deployed Siem tool(Splunk Enterprise)
🐛 Challenges & Fixes
Successfully created a functioning domain environment to support SOC monitoring and log collection.

<img width="1536" height="1024" alt="bc285d80-0784-48ac-9a53-270ddc74f5ae" src="https://github.com/user-attachments/assets/765fb069-b449-4eda-9703-e3d500e11370" />
