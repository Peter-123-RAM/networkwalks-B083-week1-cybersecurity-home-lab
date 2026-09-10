# 🔐 NETWORKWALKS B083 — Cybersecurity Home Lab Deployment

## Week 1 Project | Cybersecurity & Ethical Hacking

**Student:** Adongo Peter Oduor  
**Batch:** B083  
**Program:** Cybersecurity & Ethical Hacking  
**Week:** 1  
**Platform:** Kali Linux  
**Virtualization:** Oracle VirtualBox  
**Host Operating System:** Windows 11

---

## 📌 Project Overview

This project documents the deployment and configuration of a controlled cybersecurity laboratory using **Kali Linux running inside Oracle VirtualBox on Windows 11**.

The objective was to establish a reliable and controlled environment for practicing cybersecurity, ethical hacking, Linux administration, networking, vulnerability assessment, and future penetration-testing activities.

The completed laboratory will serve as the foundation for future hands-on cybersecurity projects throughout the NETWORKWALKS program.

---

## 🎯 Project Objectives

The objectives of this project were to:

- Install and configure Oracle VirtualBox.
- Deploy Kali Linux as a virtual machine.
- Configure the virtual machine environment.
- Configure and verify network connectivity.
- Perform basic Linux and network verification.
- Create a VM snapshot for recovery.
- Establish a controlled cybersecurity practice environment.
- Document and demonstrate the completed laboratory.

---

## 🧰 Technologies & Tools

| Technology | Purpose |
|------------|---------|
| Windows 11 | Host Operating System |
| Oracle VirtualBox | Virtualization Platform |
| Kali Linux | Cybersecurity Operating System |
| Linux Terminal | System & Network Verification |
| VirtualBox Networking | Virtual Network Connectivity |
| GitHub | Documentation & Version Control |

---

## 🏗️ Lab Architecture

```text
                    WINDOWS 11 HOST
                          │
                          ▼
                  ORACLE VIRTUALBOX
                          │
                          ▼
                    KALI LINUX VM
                          │
                 ┌────────┴────────┐
                 │                 │
          Virtual Networking   Security Tools
                 │                 │
                 ▼                 ▼
          Network Testing     Cybersecurity
                              Practice
The virtualized environment provides a controlled platform for cybersecurity learning and experimentation.

⚙️ Lab Deployment
1. Virtual Machine Deployment

Kali Linux was successfully deployed as a virtual machine using Oracle VirtualBox.

The virtual machine was configured with the necessary resources and successfully booted into the Kali Linux desktop environment.

2. Network Configuration

The Kali Linux network interface was inspected using:

ip addr

The routing table was verified using:

ip route

These commands were used to verify the network interface, assigned IP address and routing configuration.

3. Connectivity Testing

Network connectivity was tested using:

ping -c 4 8.8.8.8

DNS resolution and connectivity were also tested using:

ping -c 4 google.com

These tests were used to confirm successful network communication from the Kali Linux environment.

4. Snapshot & Recovery

A VirtualBox snapshot was created after establishing the working laboratory environment.

The snapshot provides a recovery point that can be used to restore the virtual machine to a known working state during future cybersecurity experiments.

🔍 Verification Commands

The following commands were used during the laboratory setup:

whoami

Identifies the currently logged-in user.

hostname

Displays the system hostname.

ip addr

Displays network interfaces and assigned IP addresses.

ip route

Displays the routing table.

ping -c 4 8.8.8.8

Tests IP connectivity.

ping -c 4 google.com

Tests connectivity and DNS resolution.

🛠️ Troubleshooting Approach

The laboratory setup required systematic verification of the virtual machine and network configuration.

The troubleshooting methodology followed:

Identify
   ↓
Inspect
   ↓
Test
   ↓
Troubleshoot
   ↓
Verify
   ↓
Document

This process reinforced the importance of understanding the underlying configuration before applying corrective actions.

🎥 Project Demonstration

A video demonstration has been prepared to document the completed Week 1 laboratory.

The demonstration presents the deployed Kali Linux environment and the configured VirtualBox laboratory.

Video Evidence

Week 1 Cybersecurity Lab Demonstration — B083

[PASTE YOUR VIDEO LINK HERE]

The video serves as the primary visual evidence of the completed laboratory environment.

🧠 Key Learning Outcomes

This project strengthened my practical understanding of:

Virtual machine deployment
Kali Linux
Linux system administration
IPv4 addressing
Network interfaces
Routing
VirtualBox networking
Network connectivity testing
Troubleshooting methodology
VM snapshots and recovery
Cybersecurity laboratory preparation
Technical documentation
🛡️ Security Considerations

The laboratory is intended strictly for educational and authorized cybersecurity testing.

Cybersecurity activities performed within the environment should only target systems that are owned by the tester or for which explicit authorization has been obtained.

The use of a virtualized laboratory provides a controlled environment for learning security concepts and performing authorized experiments.

🚀 Future Laboratory Development

The laboratory will progressively be expanded to support:

Network reconnaissance
Vulnerability assessment
Web application security
Digital forensics
Log analysis
SIEM exercises
Threat detection
Active Directory security
Capture-the-Flag challenges
Penetration-testing practice
🎓 Program Information

Program: NETWORKWALKS — Cybersecurity & Ethical Hacking
Batch: B083
Week: 1

This project represents the first stage of developing a practical cybersecurity laboratory and building hands-on technical skills.

👤 Author

Adongo Peter Oduor

Cybersecurity & Ethical Hacking Learner
NETWORKWALKS — Batch B083

⚠️ Disclaimer

This project is intended strictly for educational purposes.

All cybersecurity testing must be conducted against systems that are owned by the tester or for which explicit authorization has been obtained.

⭐ Building practical cybersecurity skills through hands-on learning — one lab at a time.

---

# 2. LinkedIn — updated for VIDEO ONLY

Use this version:

```text
🔐 WEEK 1 | CYBERSECURITY HOME LAB DEPLOYMENT

I’m excited to share my first hands-on project as part of the NETWORKWALKS Cybersecurity & Ethical Hacking Program — Batch B083.

🧪 PROJECT: Cybersecurity Home Lab Deployment

I successfully deployed and configured a controlled cybersecurity laboratory using Kali Linux running on Oracle VirtualBox, with Windows 11 as the host operating system.

During this project, I worked on:

🔹 Virtual machine deployment
🔹 Kali Linux configuration
🔹 Virtual networking
🔹 IPv4 network configuration
🔹 Routing and connectivity verification
🔹 Network troubleshooting
🔹 Virtual machine snapshots and recovery
🔹 Technical documentation

🧠 KEY LEARNING

This project reinforced an important cybersecurity principle: strong cybersecurity skills are built on a solid foundation of Linux, networking, virtualization and systematic troubleshooting.

The laboratory I built will serve as my controlled environment for future cybersecurity and ethical hacking exercises throughout the NETWORKWALKS program.

🎥 PROJECT DEMONSTRATION

I have attached a short video demonstrating my completed cybersecurity laboratory and the work accomplished during Week 1.

📂 GITHUB DOCUMENTATION:


I’m looking forward to continuously expanding this laboratory, working on more practical security challenges and documenting my progress throughout the program.

Special appreciation to NETWORKWALKS and Waqas Karim, CCIE, for creating a practical environment for cybersecurity learning.

🚀 Building practical skills through hands-on learning — one lab at a time.

#NETWORKWALKS #B083 #Cybersecurity #EthicalHacking #KaliLinux #VirtualBox #CybersecurityLab #Linux #Networking #InformationSecurity #GitHub #HandsOnLearning #CyberSecurityJourney
