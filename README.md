# Detection Lab

## Objective

To design and implement a Cybersecurity Detection Homelab using VirtualBox as the hypervisor, hosting Windows 10 and Kali Linux virtual machines. This lab aims to simulate a realistic enterprise environment for practicing threat detection, network monitoring, and incident response techniques. By configuring and analyzing system logs, network traffic, and attack simulations, the lab enhances hands-on skills in identifying, investigating, and mitigating cybersecurity threats.

### Skills Learned

- Setting up, configuring, and managing virtual machines using VirtualBox.
- Installing and hardening Windows 10 and Kali Linux environments.
- Creating and managing internal, bridged, and NAT networks for isolated testing.
- Monitoring logs and system activity to detect malicious behavior.
- Practicing triage, containment, and remediation of simulated attacks.
- Conducting controlled attacks from Kali Linux against Windows targets.
- Using tools like Sysmon to identify anomalies.
- Gaining hands-on experience with Windows PowerShell and Linux terminal commands.
- Identifying and testing system weaknesses using open-source tools.
- Forwarding and analyzing logs in platforms like Splunk.

### Tools Used

- Hypervisor - VirtualBox, Virtual Machines - Windows 10 and Kali Linux.
- Splunk - Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps
Step 1 - Download, Install and configure VirtualBox and Windows 10 and Kali Linux
<img width="768" height="480" alt="Virtual Box" src="https://github.com/user-attachments/assets/fc8c20d5-54b7-49e9-b0d9-ab9d445c347d" />
<img width="778" height="501" alt="image" src="https://github.com/user-attachments/assets/4ae97458-93ee-4f48-bdba-2a1997424589" />
<img width="782" height="350" alt="image" src="https://github.com/user-attachments/assets/4af2e31e-c7a8-4567-865e-05c51433309f" />

- Step 2 - Note - 192.168.20.10 for Windows 10 is a Private, Local IP address that allows devices on a home network to talk to each other and the subnet mask is 255.255.255.0
<img width="779" height="664" alt="image" src="https://github.com/user-attachments/assets/dd7c5894-0681-428a-8755-48197bc3c31c" />

- Note 192.168.20.11 for Linux is a Private, Local IP address that allows devices on a home network to talk to each other and the subnet mask is 255.255.255.0 or 24 which is interchangable
  <img width="761" height="504" alt="Linux Configure" src="https://github.com/user-attachments/assets/d61c1a33-d65b-4508-9c19-0a6cf1aed14f" />

- Step 3 - After configuring the VMs, we want to Ping the Linux machine from the Windows machine to ensure that they are communcating with each other, either through the NAT - Network Address Translation or the Internal Network.
  <img width="761" height="504" alt="Linux ping" src="https://github.com/user-attachments/assets/5a23ca81-e937-47e4-bbd5-b2d97ee5b772" />


Example below.

*Ref 1: Network Diagram*


