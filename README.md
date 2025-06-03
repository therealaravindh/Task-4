# Task-4
Elevate labs innternship Task 4 : Setup and Use a Firewall on Windows/Linux
I'm using windows and android to do this task. 

Step 1: click windows button and type windows deffender firewall with advanced security
Step 2: now click on inbound rule and create a new inbound rule to block the port 23 for telnet 
Step 3: to check the rule is working I used Netcat package from the Nmap tool 
Step 4: now open CMD with admin privilege and type the command ncat -l 23
Step 5: now open Termux app in a android device ( you can use another laptop or PC, but i don't have one) in the same network.
Step 6: now type the command ncat 192.168.1.7 ( The IP address is your laptop's IP to find that type ipconfig in your CMD)
Step 7: if it showed TIMEOUT. the rule is working fine
Step 8: now delte that inbound rule and try this commands again 
Step 9: if you type anything " heyy". It will also shown in your termux app.




