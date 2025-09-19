# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:



<img width="877" height="548" alt="Screenshot 2025-09-19 204800" src="https://github.com/user-attachments/assets/4ba49dda-927d-4380-ba34-db0c16c4e95a" />





In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


<img width="839" height="568" alt="Screenshot 2025-09-19 204812" src="https://github.com/user-attachments/assets/354a6fd8-e891-444d-bd5a-5a4ff00be0ba" />



<img width="696" height="287" alt="Screenshot 2025-09-19 204823" src="https://github.com/user-attachments/assets/79387d26-f047-4f62-a666-6b93a11102d9" />


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:


<img width="794" height="147" alt="Screenshot 2025-09-19 204844" src="https://github.com/user-attachments/assets/aa6e029a-1bac-411d-9aa5-ecd18772bd38" />



<img width="1101" height="460" alt="Screenshot 2025-09-19 204856" src="https://github.com/user-attachments/assets/c85dcf9d-9cdc-4fc4-8e73-dfe59b4de53c" />


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
