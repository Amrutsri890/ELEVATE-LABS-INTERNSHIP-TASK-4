# ELEVATE-LABS-INTERNSHIP-TASK-4
Overview

This project demonstrates the configuration and testing of Windows Firewall rules to control inbound and outbound network traffic. Firewalls are a key security feature that protect systems by blocking unauthorized access while allowing legitimate communication.

The task involved blocking insecure ports (like Telnet – port 23) and allowing essential services (like SSH – port 22) to better understand how firewalls filter traffic and enforce security policies.

🛠 Tools Used

Windows Defender Firewall (built-in)

PowerShell (Test-NetConnection command)

Ncat / Telnet (for testing connectivity)

Google (for research)

ChatGPT (for documentation support)

🎯 Objectives

Understand the role of firewalls in cybersecurity.

Configure firewall rules to allow/deny traffic on specific ports.

Test and verify firewall behavior using different tools.

Gain practical skills in traffic filtering and policy enforcement.

🔍 Task Steps

Opened Windows Defender Firewall with Advanced Security.

Created Inbound Rules to block Telnet (port 23).

Created rules to allow secure ports (e.g., SSH – port 22).

Verified rules by testing with:

Test-NetConnection (PowerShell).

telnet command.

ncat utility.

Documented results and confirmed that blocked connections failed while allowed connections succeeded.

📊 Findings

Blocked Port:

Telnet (Port 23) → Insecure protocol, connection attempts blocked.

Allowed Port:

SSH (Port 22) → Secure remote management allowed.

(Screenshots of firewall rule creation and test results should be placed in the screenshots/ folder.)

📑 Deliverables

report.md → Detailed firewall configuration report.

screenshots/ → Proof of firewall rules and test results.

README.md → Project overview (this file).

✅ Conclusion

This task provided practical experience in firewall configuration and testing. By blocking insecure connections and allowing secure ones, I learned how firewalls enforce security policies and protect systems from unauthorized access. The exercise also reinforced the importance of proper firewall management in maintaining overall cybersecurity.
