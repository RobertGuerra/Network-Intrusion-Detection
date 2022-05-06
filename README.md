# Network-Intrusion-Detection-System
School project

Project description: 
The goal of this project is to create software applications that will be launched on AWS and will be 
forwarded network packets to monitor for malicious activity or policy violations. We will utilize a SIEM 
tool to parse the data and visibly show any malicious activity on the network. 

Project setup environment:
The software will be launched on the cloud and can be started/stopped/restarted via terminal/console. 
The server containing the application will be running the NIDS software and SIEM tool. Once launched, 
the administrator can log into the SIEM console via browser and see for any flagged packets detected by the NIDS.


Project deliverables: 
- Will be setting up a server to have the NIDS and other supporting tools set up. We will have other systems 
  forwarding data to the server to monitor or any malicious activities on the network. 
- Data collected by the NIDS will then be forwarded to our SIEM tool and an administrator 
  will be able to view the console on their browser. The SIEM console will be set up to display any systems 
  on the network that are flagged for malicious activity.
- Within the network environment, we will have a system that will be sending malicious packets to test the 
  NIDS application and should be viewable on the SIEM console.
  
Project skill needed: 
- Knowledge of open-source tools such as security threat frameworks, SIEM, etc.
- Python, AWS, and Bash script languages
- Linux administrator/networking skills/knowledge
