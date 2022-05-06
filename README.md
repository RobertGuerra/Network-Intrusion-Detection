# Network-Intrusion-Detection-System
School project

My roles included doing research on AWS services, Security Information and Event Management (SIEM) and
Network Intrusion Detection System (Snort).
  Also,
  - Snort: I assisted in configuring Snort rules for detecting events such as: icmp, ssh/ssh brute force, and nmap scans
  - nmap: nmap scan during demo
  - understanding: Helped group members understand linux commands and AWS setup

Project description: 
The goal of this project was to create software application that was launched on AWS and
forward network packets to monitor for malicious activity or policy violations. We utilized a SIEM 
tool to parse the data and visibly show any malicious activity on the network. 

Project setup environment:
The software was launched on the cloud temporarily (during semester) and could be started/stopped/restarted via terminal/console. 
The server containing the application ran the NIDS software and SIEM tool. Once launched, 
the administrator was able to log into the SIEM console via browser and see any flagged packets detected by the NIDS.


Project deliverables: 
- A server along withd the NIDS and other supporting tools were set up. We ended up using Splunk to 
  forward data to the server to monitor or any malicious activities on the network. 
- Data collected by the NIDS was forwarded to our SIEM tool and an administrator 
  was be able to view the console on their browser. The SIEM console was set up to display any systems 
  on the network that are flagged for malicious activity.
- Within the network environment, we had a system (attacker) send malicious packets to test the 
  NIDS application and were able to viewable on the SIEM console.
  
Project skills needed: 
- Knowledge of open-source tools such as security threat frameworks, SIEM, etc.
- Python, AWS, and Bash script languages
- Linux administrator/networking skills/knowledge

Tools used:
- AWS console, IAM, VPC (private and public), security groups, route tables
- Linux (administration and networking)
- Snort (NIDS) along with the Data Aquisition Libraries used by Snort (DAQ)
- Security and Event Management System (Splunk/Splunk Forwarder/Dashboard)
- Python (scripting to simulate an attack using hping)

You can find a PDF of the project presentation and NIDS report in the repo (group members full names redacted for privcy)

* There is also a PDF version of AWS Educate profile which shows digital certificates for completion of
  the Cloud Computing 101 and Cybesecurity Specialist modules. This was included to show foundational knowledge of AWS.
