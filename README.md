# Cyber-Attack-Simulation-Report
# Cyber Attack Simulation Report

## Prepared by: Prime Alyn Murcia

## Objective
The purpose of this report is to simulate and document common attack vectors, including SQL Injection, Cross-Site Scripting (XSS), and Privilege Escalation, within an isolated, controlled environment. This simulation aims to:
- Identify and exploit vulnerabilities in web applications.
- Provide recommendations for mitigating security risks.
- Deploy and test security solutions such as ModSecurity Web Application Firewall (WAF) and Wazuh Security Information and Event Management (SIEM) for monitoring, threat detection, and incident response.

## Introduction
For this simulation, **Damn Vulnerable Web Application (DVWA)** was used as the intentionally vulnerable target, and **Kali Linux** served as the penetration testing platform. These tools provided a controlled environment to explore various attack techniques and defensive strategies.

### Tools and Technologies Used:
- **DVWA** – A deliberately insecure web application for security testing and learning.
- **Kali Linux** – A Debian-based OS with built-in penetration testing tools.
- **SQLmap** – Automates SQL Injection detection and exploitation.
- **Burp Suite** – Used for web application security testing.
- **Netcat** – Utility for reading and writing data across network connections.
- **Nmap** – Network discovery and vulnerability scanning tool.
- **OpenVAS** – Vulnerability scanning framework.
- **Metasploit Framework** – A powerful platform for developing and executing exploits.

### Security Solutions Implemented:
- **ModSecurity WAF** – Deployed on an Nginx web server to mitigate web-based attacks.
- **Wazuh SIEM** – Configured to monitor logs and detect malicious activities in real time.

## Environment Setup
The penetration testing and defensive configurations were established using virtual machines:
1. **Target System:** DVWA running on a web server.
2. **Attacker System:** Kali Linux with necessary tools for offensive security testing.
3. **Defensive System:** ModSecurity-enabled Nginx server and Wazuh SIEM for logging and threat detection.

## Report Contents
- **Attack Simulations:** Step-by-step execution of SQL Injection, XSS, and Privilege Escalation attacks.
- **Exploitation Analysis:** Methods used to exploit vulnerabilities and gain unauthorized access.
- **Defensive Measures:** Implementation of ModSecurity WAF and Wazuh SIEM for security hardening.
- **Mitigation Strategies:** Best practices for preventing similar attacks in real-world environments.

## Conclusion
This simulation demonstrates the importance of both offensive security testing and defensive security measures. By exploiting vulnerabilities in a controlled environment, insights were gained into how attackers operate and how security teams can better protect web applications. The deployment of ModSecurity WAF and Wazuh SIEM further highlights the need for layered security in modern IT infrastructures.

---

This README serves as an overview of the Cyber Attack Simulation Report, providing insight into the tools, methodologies, and security measures employed.

