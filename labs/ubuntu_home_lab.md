# Ubuntu Home Lab



1. Identify Network Interfaces and IP Addresses
![alt text](<../images/1 net tools, ip config.png>)
This command shows all network connections and their IP addresses on the server. This is super helpful for setting a server up / finding any devices you might need to.


---

2. Check Open Ports
![alt text](<../images/2 iconfig.png>)
![alt text](<../images/2 lsof.png>)
Lists all open ports, and the services that listen to those ports. Can be used to harden the server by removing unneeded ports. 
---


3. Analyze Network Connections
![alt text](<../images/3 netstat.png>)
Lists all network connections

---

4. Preform Network Scanning with Nmap
![alt text](<../images/4 nmap local.png>)
Scans server to find running services, open ports, and can also discover services that are unintentionally exposed.


---


5. Check for Open Ports on the Server's Network
![alt text](<../images/5 nmap server scan 1.png>)
![alt text](<../images/5 nmap server scan 2.png>)
Identifies all live hosts on the local network. Allows users to make sure no unidentified connections are present. 

---

6. Check for Services and Versions
![alt text](<../images/6 nmap SV localhost.png>)
Scans for open ports, then identifies the services attached to those ports. Can identify vulnurable software. 

---

7. Identify Potential Vulnerabilities
![alt text](<../images/7 vuln localhost.png>)
Display known vulnarabilities on the server. used for finding security issues. 
---



8. Inspect Network Traffic
![alt text](<../images/8 doesnt work.png>)
Shows all network traffic on a specific interface. 
---

9. Monitor network Connections in Real-Time
![alt text](../images/9.png)
Continously watch network connections. Real time observations. 
---


10. Check Firewall Status
![alt text](../images/10.png)
Displays firewall rules