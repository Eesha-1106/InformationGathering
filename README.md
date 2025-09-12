# Ex-02 InformationGathering
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

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois
<img width="613" height="371" alt="image" src="https://github.com/user-attachments/assets/3e04221d-5ed9-43d0-b09f-38448f8fb1c5" />
<img width="613" height="342" alt="image" src="https://github.com/user-attachments/assets/57943e24-67bc-4a77-a6aa-9fadad13ce3f" />

### Finding Hosting Company :
<img width="800" height="1200" alt="image" src="https://github.com/user-attachments/assets/47568c49-000d-499f-b382-68e819007072" />

### History of the website :
<img width="639" height="433" alt="image" src="https://github.com/user-attachments/assets/121861cb-de8e-4df6-b80c-0d1f35137092" />

### ping command :
<img width="1200" height="1500" alt="image" src="https://github.com/user-attachments/assets/de314c45-47dd-48b5-8f68-4a6f2f67af42" />

### whois :
<img width="466" height="390" alt="image" src="https://github.com/user-attachments/assets/bc32db72-d2e5-405c-9564-a8584ccb2fa6" />
<img width="460" height="404" alt="image" src="https://github.com/user-attachments/assets/40e6d0b5-c566-4b6f-952d-f17e589be035" />

### netcat :
![WhatsApp Image 2025-09-12 at 14 24 17_afdc4aab](https://github.com/user-attachments/assets/888293d3-6181-4206-a17d-2e50e2db90ab)


### nmap :
<img width="1200" height="1500" alt="image" src="https://github.com/user-attachments/assets/0d58a815-a241-4913-8ce7-4fdc646211a2" />

### whatweb :
<img width="1200" height="1500" alt="image" src="https://github.com/user-attachments/assets/eb25be0d-1bf1-4b1a-83aa-433cc7500e3f" />

### httprint :
<img width="1200" height="1500" alt="image" src="https://github.com/user-attachments/assets/f8d33d21-1dd8-43ec-b806-29ad94902564" />


### TCP traceroute :
<img width="1200" height="1500" alt="image" src="https://github.com/user-attachments/assets/10886dbe-16f2-41c9-9fa1-2cbe99f3962e" />


### UDP traceroute :
<img width="1200" height="1500" alt="image" src="https://github.com/user-attachments/assets/3162c7cf-4bbc-44f7-b27e-0fe2442ac1b8" />



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
