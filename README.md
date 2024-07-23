# Failed RDP Extraction to IP Geolocation Information
## Description
In this project I set up Microsoft Azure Sentinel (SIEM) and connected it to a live virtual machine acting as a honey pot. This allowed met to observe RDP Brute Force attacks from all around the world. This was possible due to a custom PowerShell script (in the "SecurityLogExporter.ps1" repository) and a third-party API called IP Geo Location that looks up the attacker's Geolocation info and plots it on the Azure Sentinel Map. 
![Screen Shot 2024-07-23 at 7 23 28 AM](https://github.com/user-attachments/assets/de911569-7e09-4fa4-beec-791e6c6c8bca)

## Used Language
Powershell script to extract file with failed login attempts. 

## Tools Used
ipgeolocation.io: Uses IP Address to get Geolocation API
