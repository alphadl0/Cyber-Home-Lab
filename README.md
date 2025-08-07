# Cyber-Home-Lab
I set up a basic home SOC in Azure from scratch. Using a free Azure subscription, we walk through creating a virtual machine (VM), opening it to the internet as a honeypot, and forwarding logs to a central repository. I then integrate Microsoft Sentinel to analyze real-world attack data with a map.

## This is an overview of the resources
<img width="5962" height="4362" alt="test" src="https://github.com/user-attachments/assets/4ca27808-c5b9-43b7-943c-14d29d07c52d" />

## Description
📊 Log Analytics Workspace configured to centralize system and security logs.

🔍 Microsoft Sentinel integrated for SIEM capabilities and threat detection.

🧠 KQL queries executed to identify failed login attempts and brute-force patterns.

🌍 Geolocation data uploaded, enabling visualization of attacker IPs by country.

🗺️ Attack map created to track real-time malicious activity.

## This is the attack-map
<img width="1176" height="675" alt="image" src="https://github.com/user-attachments/assets/dfe08752-8c88-4016-8efc-54c8786463b0" />
