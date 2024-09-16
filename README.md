# EX-2.InformationGathering
## Date:20/02/2024
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering


## OUTPUT:
## whois
![Screenshot 2024-09-16 133153](https://github.com/user-attachments/assets/a6c7b0bd-dda0-4842-9104-b7c06055ae2d)
## ip2location
![image](https://github.com/Darkwebnew/InformationGathering/assets/143114486/74f45ba9-b604-4445-b5c5-2ed6be140e1a)
## web archive
![Screenshot 2024-09-16 135104](https://github.com/user-attachments/assets/2a1343f7-1f80-437e-a1c8-6d29bb019881)
# Webserver Fingerprinting:
## netcat:
```
nc 172.17.52.118 80
```
## Output
![image](https://github.com/Darkwebnew/InformationGathering/assets/143114486/f38b67d8-2fc1-439e-8bcb-35ee5fb5c409)
## Nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output
![image](https://github.com/Darkwebnew/InformationGathering/assets/143114486/931ac58b-359d-409e-8ef3-206668541bcf)
## Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## Output
![image](https://github.com/Darkwebnew/InformationGathering/assets/143114486/772a0c0f-0c27-45d9-b8f1-047bd213d9e0)
![image](https://github.com/Darkwebnew/InformationGathering/assets/143114486/cde26b77-a90c-4973-bbe9-0a0e086dc1d4)
## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output
![image](https://github.com/Darkwebnew/InformationGathering/assets/143114486/8e202451-dd97-461d-86d2-7ecd4c45e86b)
# Tracing the Location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output
![image](https://github.com/Darkwebnew/InformationGathering/assets/143114486/4ac5d4e3-51f7-46ee-91f5-b4e250c904aa)
## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output
![image](https://github.com/Darkwebnew/InformationGathering/assets/143114486/0fa4acda-02fc-46f7-927e-63cb11bc0cd1)
## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
![image](https://github.com/Darkwebnew/InformationGathering/assets/143114486/5e55b5d3-0de9-45c6-a8f5-f9bcd99147a1)
## RESULT:
The information gathering techniques tools/procedure were  identified successfully
