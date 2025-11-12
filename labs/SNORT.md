SNORT is an open source network intrusion detection and prevention system created in 1998. Here in my Ubuntu home lab I will be installing and configuring SNORT in my VM. 


1. Install Snort<br>
![](../images/snort/snort%201%20abd%202.png)<br>
Use the package manager to install snort. You can run "ip a" to find your network interface


2. Configure Snort<br>
![alt text](<../images/snort/snort 3.png>) <br>
Use the command "sudo nano /etc/snort/snort.conf" to edit the configuration file of SNORT. 


3. Update / manage Snort rules<br>
![alt text](<../images/snort/snort 4.png>) <br>
Add community rules for extra commands

4. Test Snort Configuration<br>
![alt text](<../images/snort/snort config success 5.png>) <br>
Runs a configuration test to make sure SNORT is working correctly


5. Running Snort in IDS mode<br>
![alt text](<../images/snort/ids mode 1.png>) <br>
![alt text](<../images/snort/ids mode 2.png>) <br>
IDS (Intrustion Detection System) mode allows you to monitor traffic using SNORT. 


6. Viewing Snort logs<br>
![alt text](<../images/snort/step 7 logs.png>) <br>
Here you can see the logs created by SNORT running in IDS mode. 

7. Running Snort as a Daemon!<br>
SNORT Running as a background process:
![alt text](<../images/snort/SNORT bagckground running.png>) <br>
The command to stop SNORT: 
[alt text](<../images/snort/stopping snort.png>) <br>